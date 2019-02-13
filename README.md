# andy

Lien pour le rapport sur overleaf: <https://fr.overleaf.com/5579627769gjtkkkwxnwhw>


Notes design:


LiDAR - ajouter la dimension de distance aux pixels

Caméra - comme chevreuil, seulement des photos quand il y a du mouvement (on augmente l’autonomie de la batterie)

Batterie au lithium

Pour approximer le nombre de poissons dans le lac, on peut calculer la moyenne de poisson dans un mètre cube, ensuite on extrapole la moyenne sur la quantité d’eau totale du cours d’eau (ou simplement superficie*profondeur moyenne) — cause d’erreur principale = pas le même nombre de poissons pour chaque profondeur

### ALLER CHERCHER UN DÉPÔT GIT

>>> Ouvrir Git Bash dans le répertoire désiré

ou

>>> Dans la barre de l'Explorateur Windows, écrire "cmd"
>>> Entrer les commandes désirées genre <git add test.txt>


1. Configurer le nom pour git
```
git config --global user.email sam@example.com
```
2. Créer un dépôt dans le répertoire
```
git init
```
3. Aller chercher les fichiers
```
git clone <url>

exemple: git clone https://github.com/Remi-Levesque/Design1.git
```

# Ajouter un fichier au dépôt git

-1. Regarder ce qui s'est fait dans le dépôt git
```
git status
```
0. Aller chercher les fichiers qui ont été modifiés pour pas overwrite ce qui a déjà été fait
```
git pull
```
1. Spécifier le(s) fichier(s) à ajouter
```
git add -A
```
2. Écrire le commentaire
```
git commit -a -m "Ajout de file_name.ext"
```
3. Envoyer les modifications au dépôt
```
git push
ou
git push origin master
```
Si "Another git process seems to be running in this repository":

> Afficher les éléments masqués
> Supprimer le fichier .git>index.lock

SUPPRIMER UN FICHIER

1. Supprimer le fichier dans l'Explorer Windows

2. Faire les changements dans le répertoire
```
$ git commit -a -m "Suppression de <file>"
```
3. Envoyer les changements au dépôt git
```
$ git push
```
# UTILE

Regarder les fichiers qui sont pas commun à ceux du dépôt
```
git status
```
