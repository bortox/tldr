---
author: ['bl-ue', 'Nicolas Kosinski', 'François Magimel', 'marchersimon']
date: 1633592259
title: "docker-build"
description: "docker-build, Construit une image à partir d'un Dockerfile."
categories: "common"
---
> Plus d'informations : <https://docs.docker.com/engine/reference/commandline/build/>.

- Construire une image Docker en utilisant le Dockerfile du répertoire courant :

```bash
docker build .
```

- Construire une image Docker à partir d'un Dockerfile situé à une URL précisée :

```bash
docker build github.com/creack/docker-firefox
```

- Construire une image Docker et l'étiquette :

```bash
docker build --tag nom:etiquette .
```

- Ne pas utiliser le cache lors de la construction de l'image :

```bash
docker build --no-cache --tag nom:etiquette .
```

- Construire une image Docker utilisant un Dockerfile spécifique :

```bash
docker build --file Dockerfile .
```

- Construire avec des variables personnalisées définies à la volée :

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[François Magimel](mailto:magimel.francois@gmail.com) | docker-build: add French translation (#4446) | 2020-10-05T16:35:46 | [592436b997ec](https://github.com/tldr-pages/tldr/commit/592436b997ec3d1100432caf9b5342b208f091a1)

