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

Vous devez avoir un compte Github, si ce n'est pas d�j� le cas, cr�ez le. Ensuite, allez sur http://github.com/zehirmann/pi2016

Cliquez sur le bouton fork en haut � droite. Cela va cr�er une image du r�pertoire de travail pour votre compte. Vous devez alors cloner cette branche. Retournez dans vos lignes de commande, et faites un clone :

git clone http://github.com/votreNom/pi2016.git

/*Pour ajouter ses fichiers, c'est comme dans les projets pr�c�dents*/

git add "mon fichier"

git commit -m "ajout de mon fichier"

git push -u origin master

A partir de l�, votre branche est modifi�, il faut faire une demande de merge sur le site, pour qu'on puisse le mettre sur le master de base (mais si vous ne le faites pas, on pourra quand m�me voir vos branches).
Pour �a, faites un "pull request" sur le site, en pr�cisant un commentaire. Il me suffit de l'accepter pour valider �a dans la branche principal.