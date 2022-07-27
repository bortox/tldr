---
author: ['Guido Lena Cota']
date: 1604389769
title: "git tag, TLDR Pages"
description: "git tag, Crea, elenca, cancella o verifica tag."
categories: "common"
---
> Un tag è un riferimento statico a uno specifico commit.

> Maggiori informazioni: <https://git-scm.com/docs/git-tag>.

- Mostra tutti i tag:

```bash
git tag
```

- Crea un tag con un nome, puntandolo al commit corrente:

```bash
git tag nome_tag
```

- Crea un tag con un nome, puntandolo ad un dato commit:

```bash
git tag nome_tag commit
```

- Crea un tag annotandolo con un messaggio:

```bash
git tag nome_tag -m messaggio_tag
```

- Cancella un tag, dato il suo nome:

```bash
git tag -d nome_tag
```

- Scarica tag aggiornati da upstream:

```bash
git fetch --tags
```

- Mostra tutti i tag i cui predecessori includono uno specifico commit:

```bash
git tag --contains commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

