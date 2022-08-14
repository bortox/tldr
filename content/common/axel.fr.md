---
author: ['Nicolas Hansse']
date: 1660422960
title: "axel"
description: "axel, Accélérateur de téléchargement."
categories: "common"
---
> Supporte HTTP, HTTPS, et FTP.

> Plus d'informations : <https://github.com/axel-download-accelerator/axel>.

- Télécharge depuis une URL vers un fichier :

```bash
axel url
```

- Télécharge et spécifie le nom de fichier :

```bash
axel url -o nom_de_fichier
```

- Télécharge avec plusieurs connections :

```bash
axel -n nombre_de_connections url
```

- Recherche des miroirs :

```bash
axel -S nombre_de_miroirs url
```

- Limite la vitesse de téléchargement (en octets par secondes) :

```bash
axel -s vitesse url
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | avrdude, axel: add French translation (#8339) | 2022-08-13T22:36:00 | [eb9c2d12fbfd](https://github.com/tldr-pages/tldr/commit/eb9c2d12fbfd34fd561510e2c3aea3cfe3a82fcd)

