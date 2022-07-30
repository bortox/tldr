---
author: ['Marco Bonelli']
date: 1578698516
title: "git gc"
description: "git gc, Ottimizza il repository locale ripulendolo dai file non necessari."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-gc>.

- Ottimizza il repository:

```bash
git gc
```

- Ottimizza il repository in modo più aggressivo, impiegando più tempo:

```bash
git gc --aggressive
```

- Non eliminare gli oggetti non tracciati (sono eliminati di default):

```bash
git gc --no-prune
```

- Non mostrare alcun output:

```bash
git gc --quiet
```

- Mostra utilizzo completo:

```bash
git gc --help
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | git-gc: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [be3ea1e88b4c](https://github.com/tldr-pages/tldr/commit/be3ea1e88b4c5f8acc07ecdc09977bfec0a93b64)

