---
author: ['Locour', 'Yunkz', 'François Magimel', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1634145825
title: "docker-compose"
description: "docker-compose, Exécute et gère des applications au travers de plusieurs conteneurs Docker."
categories: "common"
---
> Plus d'informations : <https://docs.docker.com/compose/reference/>.

- Liste tous les conteneurs en cours d'exécution :

```bash
docker-compose ps
```

- Crée et démarre en arrière-plan tous les conteneurs décrits dans le fichier `docker-compose.yml` du répertoire courant :

```bash
docker-compose up -d
```

- Démarre tous les conteneurs après les avoir recréés si nécessaire :

```bash
docker-compose up --build
```

- Démarre tous les conteneurs spécifiés dans un fichier compose alternatif :

```bash
docker-compose --file chemin/vers/fichier up
```

- Arrête tous les conteneurs en cours d'exécution :

```bash
docker-compose stop
```

- Arrête et supprime tous les conteneurs, réseaux, images et volumes :

```bash
docker-compose down --rmi all --volumes
```

- Affiche et suit la journalisation de tous les conteneurs :

```bash
docker-compose logs --follow
```

- Affiche et suit la journalisation pour un conteneurs spécifique :

```bash
docker-compose logs --follow nom_container
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Yunkz](mailto:50922840+Yunkz@users.noreply.github.com) | docker-compose: sync French translation (#5856) add logs for a specific container | 2021-04-30T13:26:46 | [7ebac331889f](https://github.com/tldr-pages/tldr/commit/7ebac331889fe96b08baf6a83f13858aa7a0df69)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[François Magimel](mailto:magimel.francois@gmail.com) | docker-compose: add French translation (#4447) | 2020-10-05T21:57:16 | [6db7c0130561](https://github.com/tldr-pages/tldr/commit/6db7c0130561e6e6661f2fae10fa78dad057b592)

