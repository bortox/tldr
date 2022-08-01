---
author: ['Nicolas Hansse']
date: 1659300031
title: "arduino-builder"
description: "arduino-builder, Un outil en ligne de commande pour compiler des croquis arduino."
categories: "common"
---
> AVERTISSEMENT DE DÉPRÉCIATION: Cet outil a été retiré au profit de `arduino`.

> Plus d'informations : <https://github.com/arduino/arduino-builder>.

- Construis un croquis :

```bash
arduino-builder -compile chemin/vers/croquis.ino
```

- Spécifie the niveau de débogage (1 à 10, 5 par défaut) :

```bash
arduino-builder -debug-level niveau
```

- Spécifie un dossier de construction :

```bash
arduino-builder -build-path chemin/vers/dossier/de/construction
```

- Utilise un fichier d'option de construction, au lieu de spécifier `--hardware`, `--tools`, etc. Manuellement à chaque fois :

```bash
arduino-builder -build-options-file chemin/vers/construction.options.json
```

- Active le mode verbeux :

```bash
arduino-builder -verbose true
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | arduino, arduino-builder: add French translation (#8247) | 2022-07-31T22:40:31 | [21d32a1a0084](https://github.com/tldr-pages/tldr/commit/21d32a1a0084bdc54e82ff86338c81483e839507)

