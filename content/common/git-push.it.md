---
author: ['Guido Lena Cota']
date: 1602000615
title: "git push, TLDR Pages"
description: "git push, Invia i commit a un repository remoto."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-push>.

- Invia le modifiche fatte nel ramo corrente locale al corrispondente ramo remoto:

```bash
git push
```

- Invia le modifiche fatte in uno specifico ramo locale al corrispondente ramo remoto:

```bash
git push nome_repository_remoto nome_ramo
```

- Pubblica il ramo corrente in un repository remoto, specificando il nome del ramo remoto:

```bash
git push nome_repository_remoto -u nome_ramo_remoto
```

- Invia le modifiche fatte in ogni ramo locale ai corrispondenti rami remoti:

```bash
git push --all nome_repository_remoto
```

- Cancella un ramo di un repository remoto:

```bash
git push nome_repository_remoto --delete nome_ramo_remoto
```

- Cancella i rami remoti che non hanno un ramo locale corrispondente:

```bash
git push --prune nome_repository_remoto
```

- Pubblica i tag che non sono già presenti nel repository remoto:

```bash
git push --tags
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-push: add it translation (#4521) | 2020-10-06T18:10:15 | [be1868927ddf](https://github.com/tldr-pages/tldr/commit/be1868927ddf6baaea73b7f2ce6d365dc89436de)

