---
author: ['Marco Bonelli']
date: 1578698516
title: "git-grep"
description: "git-grep, Cerca stringhe nello storico dei file tracciati nel repository."
categories: "common"
---
> Supporta molti degli stessi parametri accettati dal comando `grep` tradizionale.

> Maggiori informazioni: <https://git-scm.com/docs/git-grep>.

- Cerca una stringa nei file tracciati:

```bash
git grep stringa_ricercata
```

- Cerca una stringa nei file tracciati che soddisfano un dato pattern:

```bash
git grep stringa_ricercata -- file_glob_pattern
```

- Cerca una stringa nei file tracciati, sottomoduli inclusi:

```bash
git grep --recurse-submodules stringa_ricercata
```

- Cerca una stringa in uno dato momento della cronologia del repository:

```bash
git grep stringa_ricercata HEAD~2
```

- Cerca una stringa in tutti i rami:

```bash
git grep stringa_ricercata $(git rev-list --all)
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | git-grep: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [1d759b1e2b14](https://github.com/tldr-pages/tldr/commit/1d759b1e2b1440b62c603b3b7d1519a881b0319b)

