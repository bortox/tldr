---
author: ['bl-ue', 'marchersimon']
date: 1633592259
title: "docker container, TLDR Pages"
description: "docker container, Gère les conteneurs Docker."
categories: "common"
---
> Plus d'informations : <https://docs.docker.com/engine/reference/commandline/container/>.

- Liste les conteneurs Dockers en cours d'exécution :

```bash
docker container ls
```

- Démarre un ou plusieurs conteneur arrêtés :

```bash
docker container start nom_conteneur_1 nom_conteneur_2
```

- Tue un ou plusieurs conteneurs en cours d'exécution :

```bash
docker container kill nom_conteneur
```

- Arrête un ou plusieurs conteneurs en cours d'exécution :

```bash
docker container stop nom_conteneur
```

- Mets en pause tous les processus d'un ou plusieurs conteneurs :

```bash
docker container pause nom_conteneur
```

- Affiche des informations détaillées sur un ou plusieurs conteneurs :

```bash
docker container inspect nom_conteneur
```

- Exporte le système de fichiers d'un conteneur sous forme d'archive Tar :

```bash
docker container export nom_conteneur
```

- Crée une nouvelle image à partir des changements d'un conteneur :

```bash
docker container commit nom_conteneur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | docker-container: sync translations with PR #5067 (#5356) | 2021-03-08T20:30:58 | [a8b4d5f55b2d](https://github.com/tldr-pages/tldr/commit/a8b4d5f55b2d93890e414c9c2e83d06f6939bcda)

