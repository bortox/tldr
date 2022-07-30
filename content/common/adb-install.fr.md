---
author: ['Nicolas Hansse']
date: 1642517209
title: "adb install"
description: "adb install, Android Debug Bridge Install: Pousse des paquets vers une instance d'émulateur Android ou un appareil Android."
categories: "common"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/adb>.

- Pousse une application Android vers l'émulateur/l'appareil :

```bash
adb install chemin/vers/le/fichier.apk
```

- Réinstalle une application existante, tout en gardant ses données :

```bash
adb install -r chemin/vers/le/fichier.apk
```

- Accorde toutes les permissions listées dans le manifeste de l'application :

```bash
adb install -g chemin/vers/le/fichier.apk
```

- Mets à jour rapidement un paquet en mettant à jour uniquement les parties de l'APK qui ont changé :

```bash
adb install --fastdeploy chemin/vers/le/fichier.apk
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adb-install, adb-reverse, adb-shell: add French translation (#7667) | 2022-01-18T15:46:49 | [cf250037d7ba](https://github.com/tldr-pages/tldr/commit/cf250037d7babaca84dfa993414eb9b722be28f2)

