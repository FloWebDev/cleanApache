# cleanApache

## Script cleanApache

Le script cleanApache sert à supprimer l'ensemble des logs du serveur Apache installé dans un environnement Linux (Debian/Ubuntu).

**Attention, ce script n'effectue aucune copie des logs. Les logs seront définitivement supprimés. Pensez donc à faire une copie du dossier Apache (si besoin).**

Pour utiliser le script, vous devez tout d'abord rendre celui-ci exécutable avec la commande suivante (avec les droits root et en vous plaçant dans le dossier du script) :

`sudo chmod +x cleanapache`

Vous pourrez ensuite effectuer la commande suivante pour exécuter le script :

`sudo ./cleanapache` (avec les droits root et en vous plaçant dans le dossier du script)

Une fois la commande effectuée, le script vous indiquera la taille de l'ensemble des logs du dossier "apache2".

Un message vous demandera de confirmer ou non la suppression de l'ensemble des logs liés à Apache.

Si besoin, vous pouvez intégrer le script comme commande en le plaçant dans un des répertoires du PATH.
Vous pouvez visualiser ces répertoires spéciaux avec : `echo $PATH`

Vous pourrez alors exécuter directement la commande sans le `./` avec `sudo cleanapache`

Si besoin ou utilité, pour débugger le script : `bash -x ./cleanapache`

## Informations générales sur les scripts shell

Voici les noms de quelques-uns des principaux shells qui existent.
- sh : Bourne Shell. L'ancêtre de tous les shells.
- bash : Bourne Again Shell. Une amélioration du Bourne Shell, disponible par défaut sous Linux et Mac OS X.
- ksh : Korn Shell. Un shell puissant assez présent sur les Unix propriétaires, mais aussi disponible en version libre, compatible avec bash.
- csh : C Shell. Un shell utilisant une syntaxe proche du langage C.
- tcsh : Tenex C Shell. Amélioration du C Shell.
- zsh : Z Shell. Shell assez récent reprenant les meilleures idées de bash, ksh et tcsh.
