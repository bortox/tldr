---
author: ['Marco Bonelli']
date: 1578698516
title: "git fetch, TLDR Pages"
description: "git fetch, Scarica oggetti e riferimenti da un repository remoto."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-fetch>.

- Scarica le ultime modifiche dal repository remoto di origine (upstream) di default, se definito:

```bash
git fetch
```

- Scarica i nuovi rami da un dato repository remoto di origine:

```bash
git fetch nome_repository_remoto
```

- Scarica le ultime modifiche da tutti i repository remoti di origine:

```bash
git fetch --all
```

- Scarica anche i tag dal repository remoto di origine:

```bash
git fetch --tags
```

- Elimina i riferimenti locali ai rami remoti che sono stati eliminati dal repositoy di origine:

```bash
git fetch --prune
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | git fetch: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [c14f06d0e395](https://github.com/tldr-pages/tldr/commit/c14f06d0e395da6f9ed35f5cd7bed408c66926f2)

