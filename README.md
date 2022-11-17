# Exemples du cours sur Python
 
## Preparation virtual env

1. Installer la version python3
2. Se positionner dans le repertoire du projet
3. Créer un environnement virtuel

`python3 -m venv .`

4. Activer votre environnement virtuelle

OS|Shell|Commaande
--|-----|---------
Windows|dos|C:\\{venv}\\Scripts\\activate.bat
Windows|PowerShell|PS C:\\> <venv>\\Scripts\\Activate.ps1
Linux,Mac|shell,ksh|source <venv>/bin/activate

Source : https://docs.python.org/fr/3/library/venv.html

## Lancement jupyter-lab
Executer la commande

Port|Commaande
--|-------------
8888| ` jupyter lab`
Autre port|` jupyter lab --port=<port>`

