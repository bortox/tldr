---
author: ['Gatien']
date: 1650411679
title: "code, TLDR Pages"
description: "code, Éditeur de code multiplateforme et extensible."
categories: "common"
---
> Plus d'informations : <https://github.com/microsoft/vscode>.

- Démarre Visual Studio Code :

```bash
code
```

- Ouvre des fichiers/répertoires spécifiques :

```bash
code chemin/vers/fichier_ou_répertoire1 chemin/vers/fichier_ou_répertoire2 ...
```

- Compare deux fichiers spécifiques :

```bash
code --diff chemin/vers/fichier1 chemin/vers/fichier2
```

- Ouvre des fichiers/répertoires spécifiques dans une nouvelle fenêtre :

```bash
code --new-window chemin/vers/fichier_ou_répertoire1 chemin/vers/fichier_ou_répertoire2 ...
```

- Installe/désinstalle une extension spécifique :

```bash
code --install|uninstall-extension éditeur.extension
```

- Affiche les extensions installées :

```bash
code --list-extensions
```

- Affiche les extensions installées avec leurs versions :

```bash
code --list-extensions --show-versions
```

- Démarre l'éditeur en tant que super utilisateur (root) tout en stockant les données utilisateur dans un répertoire spécifique :

```bash
sudo code --user-data-dir chemin/vers/répertoire
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | chromium, code, gimp, powershell : add French translation (#8037) * translate code in French * translate powershell in French * switch [...] | 2022-04-20T01:41:19 | [fad355136f6b](https://github.com/tldr-pages/tldr/commit/fad355136f6b12812e588e2d05b9dec91dd88f8b)

