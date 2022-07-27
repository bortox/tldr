---
author: ['Nicolas Hansse']
date: 1657896223
title: "AdGuardHome, TLDR Pages"
description: "AdGuardHome, Un logiciel réseau pour bloquer les pubs et les traqueurs."
categories: "common"
---
> Plus d'informations : <https://github.com/AdguardTeam/AdGuardHome>.

- Lance AdGuard Home :

```bash
AdGuardHome
```

- Lance AdGuard Home avec une configuration spécifique :

```bash
AdGuardHome --config chemin/vers/AdGuardHome.yaml
```

- Configure le répertoire de travail où les données seront stockées :

```bash
AdGuardHome --work-dir chemin/vers/répertoire
```

- Installe ou désinstalle AdGuard Home comme un service :

```bash
AdGuardHome --service install|uninstall
```

- Démarre le service AdGuard Home :

```bash
AdGuardHome --service start
```

- Recharge la configuration pour le service AdGuard Home :

```bash
AdGuardHome --service reload
```

- Éteint ou redémarre le service AdGuard Home :

```bash
AdGuardHome --service stop|restart
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adguardhome, adscript, ag: add French translation (#8197) | 2022-07-15T16:43:43 | [69d02dd1e288](https://github.com/tldr-pages/tldr/commit/69d02dd1e28808ed632a954eb2d81469518626f2)

