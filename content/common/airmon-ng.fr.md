---
author: ['Nicolas Hansse']
date: 1658420098
title: "airmon-ng"
description: "airmon-ng, Active le mode surveillance sur les appareils sans fils."
categories: "common"
---
> Plus d'informations : <https://www.aircrack-ng.org/doku.php?id=airmon-ng>.

- Liste les appareils sans fils et leurs statuts :

```bash
sudo airmon-ng
```

- Allume le mode surveillance sur un appareil spécifique :

```bash
sudo airmon-ng start wlan0
```

- Tue les processus nuisibles qui utilisent les appareils sans fils :

```bash
sudo airmon-ng check kill
```

- Éteint le mode surveillance pour une interface réseau spécifique :

```bash
sudo airmon-ng stop wlan0mon
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | agate, airmon-ng, airpaste: add French translation (#8202) | 2022-07-21T18:14:58 | [4f9ac0bf0c92](https://github.com/tldr-pages/tldr/commit/4f9ac0bf0c92e7eb3d72f48394134a3afd3707ce)

