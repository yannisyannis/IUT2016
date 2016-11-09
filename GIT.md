GIT :

DOC : 
	http://pioupioum.fr/developpement/git-alias-productivite.html
	Pro-GIT //PDF Gratuit, sinon payant
	git-scm.org //SIte pour se rappeler de tout ce qu'on peut faire avec GIT (Visual Cheat Sheet)
	https://onlywei.github.io/explain-git-with-d3/


Explication GIT :

--------------------------------------------------------------------------------
| Workspace		| Index/Cache/Staging		| Repository		|
--------------------------------------------------------------------------------
| fichiers locaux	| Fichiers sur serveur GIT	| dossier commun	|
--------------------------------------------------------------------------------


Commandes :

	git init //initialise un dépôt GIT dans le répertoire courant. Sur Windows : msgit, cygwin

	git add [fichier] //ajouter le fichier dans la base de données GIT, dans son index

	git add . //ajouter tous les fichiers du répertoire courant dans l'index du GIT

	git commit -m [message] //commit tous les fichiers du serveur GIT

	git log //voir tous les commit effectués

	git diff //obtenir les différences entre les fichiers locaux et les commited

	git checkout [fichier] //Récupérer les fichiers de l'index de GIT

	git status //Affiche les différences entre les fichiers du répertoire courant et ceux de l'index GIT

	git config --global --add alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit --all" //Fait un alias
	git lol

	git reset -- fichier // "--" séparateur entre arguments et fichiers

	git branch [nom branche] //Crée la branche ou te déplace dans la branche

	git branch //Affiche toutes les branches

	git branch -d [nom branche] //supprimer l'ID de la branche mais pas les données dedans. On peut recréer la branche si on connaît son ID

	git merge [branche] //récupère les modifications des fichiers dans la branche



Infos :

HEAD : branche courante commited
HEAD~ : branche précédente commited
HEAD~2 : branche d'avant

	


