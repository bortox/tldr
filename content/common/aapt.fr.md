---
author: ['Nicolas Hansse']
date: 1644837146
title: "aapt"
description: "aapt, Android Asset Packaging Tool."
categories: "common"
---
> Compile et empaquette les ressources d'une application Android.

> Plus d'informations : <https://elinux.org/Android_aapt>.

- Liste les fichiers contenus une archive APK :

```bash
aapt list chemin/vers/app.apk
```

- Affiche les metadatas d'une application (version, autorisations, etc.) :

```bash
aapt dump badging chemin/vers/app.apk
```

- Créé une nouvelle archive APK avec les fichiers venant d'un dossier spécifique :

```bash
aapt package -F chemin/vers/app.apk chemin/vers/le/dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aapt, ab: add French translation (#7723) * aapt, ab: add French translation * Update pages.fr/common/aapt.md Co-authored-by: Emily [...] | 2022-02-14T12:12:26 | [b1326296cda4](https://github.com/tldr-pages/tldr/commit/b1326296cda429c77ea5754896b0ad68f8883ca8)

