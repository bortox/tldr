---
author: ['Nicolas Hansse']
date: 1660526438
title: "avrdude"
description: "avrdude, Pilotes pour programmer les microcontrôleurs Atmel AVR."
categories: "common"
---
> Plus d'informations : <https://www.nongnu.org/avrdude/>.

- Lire le contenu du microcontrôleur AVR :

```bash
avrdude -p appareil_AVR -c programmeur -U flash:r:fichier.hex:i
```

- Programme le microcontrôleur AVR :

```bash
avrdude -p appareil_AVR -c programmeur -U flash:w:fichier.hex
```

- Affiche les appareils AVR disponibles :

```bash
avrdude -p \?
```

- Affiche les programmeurs AVR disponibles :

```bash
avrdude -c \?
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | avrdude: edit French translation (#8346) | 2022-08-15T03:20:38 | [2cfae1bf2f45](https://github.com/tldr-pages/tldr/commit/2cfae1bf2f4559ed511588ef3917c0699ae5dc07)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | avrdude, axel: add French translation (#8339) | 2022-08-13T22:36:00 | [eb9c2d12fbfd](https://github.com/tldr-pages/tldr/commit/eb9c2d12fbfd34fd561510e2c3aea3cfe3a82fcd)

