---
author: ['Nicolas Hansse']
date: 1658320829
title: "androguard"
description: "androguard, Outil d’ingénierie inverse pour les applications Android. Écrit en Python."
categories: "common"
---
> Plus d'informations : <https://github.com/androguard/androguard>.

- Affiche le manifest d'application Android :

```bash
androguard axml chemin/vers/app.apk
```

- Affiche les métadonnées de l'application (version et id d'application) :

```bash
androguard apkid chemin/vers/app.apk
```

- Décompile le code Java de l'application :

```bash
androguard decompile chemin/vers/app.apk --output chemin/vers/dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | androguard, ani-cli: add French translation (#8212) | 2022-07-20T14:40:29 | [d61c70a6334b](https://github.com/tldr-pages/tldr/commit/d61c70a6334ba745f1dc70800245b7fd80c2254c)

