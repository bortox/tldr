---
author: ['Nicolas Hansse']
date: 1633372595
title: "getprop, TLDR Pages"
description: "getprop, Affiche les informations des propriétés système Android."
categories: "android"
---
> Plus d'informations : <https://manned.org/getprop>.

- Affiche les informations des propriétés système Android :

```bash
getprop
```

- Affiche les informations d'une propriété spécifique :

```bash
getprop prop
```

- Affiche le niveau API du SDK :

```bash
getprop ro.build.version.sdk
```

- Affiche la version d'Android :

```bash
getprop ro.build.version.release
```

- Affiche le modèle de l'appareil Android :

```bash
getprop ro.vendor.product.model
```

- Affiche le status du déblocage OEM :

```bash
getprop ro.oem_unlock_supported
```

- Affiche l'adresse MAC de la carte Wi-FI Android :

```bash
getprop ro.boot.wifimacaddr
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

