# Teacher Story

Jeu gratuit pour Windows, d'après le jeu original *Teacher Story* de Motion Twin.

Ce dépôt ne contient que les versions publiées du jeu, prêtes à installer.

## Installer

1. Téléchargez `TeacherStory-x.y.z.zip` dans la
   [dernière version](https://github.com/TommyDDR/TeacherStory-releases/releases/latest).
2. Extrayez le zip dans un dossier où vous pouvez écrire : Documents, un dossier
   Jeux... **Pas dans Program Files** : le jeu ne pourrait pas se mettre à jour.
3. Lancez `TeacherStory.exe`, dans le dossier `TeacherStory` extrait.

Configuration requise : Windows 10 ou plus récent, 64 bits.

## Avertissement de Windows au premier lancement

Le jeu n'est pas signé numériquement. Windows peut afficher « Windows a protégé
votre ordinateur » : cliquez sur **Informations complémentaires**, puis
**Exécuter quand même**.

Certains antivirus signalent à tort les programmes écrits en AutoIt. Pour
vérifier que votre téléchargement est intact, comparez son empreinte à celle du
fichier `.sha256` publié avec chaque version :

```
certutil -hashfile TeacherStory-x.y.z.zip SHA256
```

## Mises à jour

Elles sont automatiques : à chaque lancement, `TeacherStory.exe` vérifie s'il
existe une nouvelle version, la propose, puis l'installe. Votre progression est
conservée.

## Progression et journaux

Ils sont rangés dans `%LOCALAPPDATA%\TeacherStory\` (à coller dans la barre
d'adresse de l'Explorateur) :

- `savegame.db` : votre progression. Supprimer le dossier du jeu ne l'efface
  pas.
- `logs\` : `game.log` et `launcher.log`, le journal du jeu et celui des mises à
  jour.

## Un problème ?

Prévenez directement l'auteur du jeu, en décrivant ce que vous faisiez et en
joignant les fichiers du dossier `%LOCALAPPDATA%\TeacherStory\logs\`.

## Licence

Le jeu et les ressources du jeu original sont distribués selon les termes de la
licence Creative Commons Attribution - Pas d'Utilisation Commerciale - Partage
dans les Mêmes Conditions 4.0 International (CC BY-NC-SA 4.0). Ressources
originales © Motion Twin. Voir [LICENSE.txt](LICENSE.txt).
