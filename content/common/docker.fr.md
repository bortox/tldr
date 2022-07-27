---
author: ['Nicolas Hansse', 'Raizo62', 'François Magimel', 'bl-ue', 'marchersimon']
date: 1640867821
title: "docker, TLDR Pages"
description: "docker, Gestion des conteneurs et des images Docker."
categories: "common"
---
> Certaines commandes comme `docker run` ont leur propre documentation.

> Plus d'informations : <https://docs.docker.com/engine/reference/commandline/cli/>.

- Liste tous les conteneurs Docker (en cours d'exécution ou arrêtés) :

```bash
docker ps --all
```

- Démarre un conteneur à partir d'une image, avec un nom personnalisé :

```bash
docker run --name nom_conteneur image
```

- Démarre ou arrête un conteneur existant :

```bash
docker start|stop nom_conteneur
```

- Télécharge une image depuis un registre Docker :

```bash
docker pull image
```

- Affiche les images déjà téléchargées :

```bash
docker images
```

- Ouvre un shell dans un conteneur déjà en cours d'exécution :

```bash
docker exec -it nom_conteneur sh
```

- Supprime un conteneur arrêté :

```bash
docker rm nom_conteneur
```

- Récupère et suit les journaux de message d'un conteneur :

```bash
docker logs -f nom_conteneur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Raizo62](mailto:silicium62-github@yahoo.fr) | docker: add docker images example (#7567) | 2021-12-30T13:37:01 | [f126048f0358](https://github.com/tldr-pages/tldr/commit/f126048f03580200edf9ad8fd66d7d134b3779d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | *: mention subcommands in FR translations (#6823) | 2021-10-06T22:45:59 | [b0e0a6e58cfb](https://github.com/tldr-pages/tldr/commit/b0e0a6e58cfbff6cb7041a4d37b1b46ddac79941)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[François Magimel](mailto:magimel.francois@gmail.com) | docker: add French translation (#4444) | 2020-10-05T16:16:09 | [d51a9b6d8b82](https://github.com/tldr-pages/tldr/commit/d51a9b6d8b8238c4159d2370cdb4483f84d45bab)

