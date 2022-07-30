---
author: ['Nicolas Hansse']
date: 1658420098
title: "airpaste"
description: "airpaste, Partage des messages et des fichiers sur le même réseau en utilisant mDNS."
categories: "common"
---
> Plus d'informations : <https://github.com/mafintosh/airpaste>.

- Attend un message et l'affiche une fois reçu :

```bash
airpaste
```

- Envoie un message :

```bash
echo text | airpaste
```

- Envoie un fichier :

```bash
airpaste < chemin/vers/fichier
```

- Recevoir un fichier :

```bash
airpaste > chemin/vers/fichier
```

- Crée ou rejoins un canal :

```bash
airpaste nom_du_canal
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | agate, airmon-ng, airpaste: add French translation (#8202) | 2022-07-21T18:14:58 | [4f9ac0bf0c92](https://github.com/tldr-pages/tldr/commit/4f9ac0bf0c92e7eb3d72f48394134a3afd3707ce)

