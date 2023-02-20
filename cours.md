### Dev web

### Definitions
Le depot git est le dossier dans le quel se trouve les données que l'on souhaite versionner. On y trouve un dossier caché ".git"

### Cours
Ceci est une commande :
```shell
    Mkdir test 
```

Ceci est du code :
```javascript
const test = 'Hello World';
```

La commande : 
```
    git init
```
Permet d'initialiser un depot Git local dans le repertoire courant. Cela se traduit par la presence d'un dossier cache `.git` a la racine du dépot

L'édition ou l'ajout de fichier dans ce repository sera dectecte par Git, pour le visualiser dans le terminal on utilse la commande:
```
    git status
```

Avant de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande:
```
    git add <nom de fichier>
```

la sauvegarde s'effectue ensuite avec la commande:
```
    git commit -m "message de commit"
```

Elle retourne :
```
Initialized empty Git repository in C:/Users/omsanjuanc OneDrive  - bourg-habitat.com/Documents/ISITECH/DEV/.git/
```

Pour vérifier l'état de votre depot Git utiliser la commande:
```
git status
```
Elle permet aussi de voir la branche

Pour renommer une branche utiliser
```
git branch -M xxx
```
Pour suivre un dépot faire la commande:
```
git add <file>
```
### Commit:

Cette commande permet de se déplacer dans les différentes version du git
```
git commit
```


