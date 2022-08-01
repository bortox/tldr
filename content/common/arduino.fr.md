---
author: ['Nicolas Hansse']
date: 1659300031
title: "arduino"
description: "arduino, Arduino Studio - Environnement de Développement Intégré pour la plateforme Arduino."
categories: "common"
---
> Plus d'informations : <https://github.com/arduino/Arduino/blob/master/build/shared/manpage.adoc>.

- Construis un croquis :

```bash
arduino --verify chemin/vers/croquis.ino
```

- Construis et téléverse un croquis :

```bash
arduino --upload chemin/vers/croquis.ino
```

- Construis et téléverse un croquis vers un Arduino Nano avec un CPU Atmega328p, connecté sur le port `/dev/ttyACM0` :

```bash
arduino --board arduino:avr:nano:cpu=atmega328p --port /dev/ttyACM0 --upload chemin/vers/croquis.ino
```

- Configure la préférence `nom` à une valeur `valeur` :

```bash
arduino --pref nom=valeur
```

- Construis un croquis, mets le résultat de ce dernier dans un dossier, et réutilise n'importe quelles versions précédentes dans ce dossier :

```bash
arduino --pref build.path=chemin/vers/dossier/de/construction --verify chemin/vers/croquis.ino
```

- Sauvegarde toutes préférences (modifiées) dans un fichier `preferences.txt` :

```bash
arduino --save-prefs
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | arduino, arduino-builder: add French translation (#8247) | 2022-07-31T22:40:31 | [21d32a1a0084](https://github.com/tldr-pages/tldr/commit/21d32a1a0084bdc54e82ff86338c81483e839507)

