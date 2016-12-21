# tuto git
Pour configurer le git sous Windows:

T�l�chargez git sur https://git-scm.com/downloads
cochez git GUI et git bash, pour pouvoir taper des commandes en console.

Dans l'explorateur, allez dans le dossier o� vous voulez travailler.
Clic droit -> git Bash Here (si vous n'avez pas ce choix, c'est que vous l'avez mal install�)

/*Pour initialiser git dans le dossier*/

git init

/*Pour vous param�trer dans le git*/

git config --global user.email "vincent.montigny45@gmail.com"   //en changeant l'adresse

git config --global user.name "Vincent Montigny"		//en changeant le nom

/*Pour cloner le r�pertoire de travail*/

git clone http://github.com/zehirmann/pi2016.git

/*Pour ajouter ses fichiers*/

git add "mon fichier"

git commit -m "ajout de mon fichier"

git push -u origin master