---
author: ['bl-ue', 'Ivor Benderavage', 'marchersimon']
date: 1633592259
title: "pipenv"
description: "pipenv, Workflow de développement simple et unifié pour Python."
categories: "common"
---
> Gère les paquets et l'environnement virtuel d'un projet.

> Plus d'informations : <https://pypi.org/project/pipenv>.

- Crée un nouveau projet :

```bash
pipenv
```

- Crée un nouveau projet à l'aide de Python 3 :

```bash
pipenv --three
```

- Installe un paquet :

```bash
pipenv install paquet
```

- Installe toutes les dépendances d'un projet :

```bash
pipenv install
```

- Installe toutes les dépendances d'un projet (y compris les paquets de développement) :

```bash
pipenv install --dev
```

- Désinstalle un paquet :

```bash
pipenv uninstall paquet
```

- Démarre une session de commandes dans l'environnement virtuel :

```bash
pipenv shell
```

- Génère un `requirements.txt` (une liste de dépendances) pour un projet :

```bash
pipenv lock --requirements
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | pipenv: add example for not dev packages (#4880) | 2020-11-01T14:11:33 | [e009d7ceba4a](https://github.com/tldr-pages/tldr/commit/e009d7ceba4a21a7920c47f78f4f2d2bf6810854)

