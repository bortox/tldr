---
author: ['Marco Bonelli', 'Zlatan Vasović']
date: 1595473581
title: "git diff, TLDR Pages"
description: "git diff, Mostra le modifiche ai file tracciati."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-diff>.

- Mostra le modifiche non ancora nell'area di stage:

```bash
git diff
```

- Mostra tutte le modifiche non ancora salvate in un commit (incluse quelle nell'area di stage):

```bash
git diff HEAD
```

- Mostra solo le modifiche nell'area di stage (aggiunte, ma non ancora committate):

```bash
git diff --staged
```

- Mostra le modifiche di tutti i commit a partire da una certa data/ora (un'espressione temporale come "1 week 2 days" o una data ISO):

```bash
git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}'
```

- Mostra solo i nomi dei file modificati a partire da un dato commit:

```bash
git diff --name-only commit
```

- Stampa un riepilogo dei file creati, rinominati o la cui modalità è cambiata a partire da un dato commit:

```bash
git diff --summary commit
```

- Confronta le versioni di un dato file tra due rami o commit:

```bash
git diff ramo_1..ramo_2 [--] percorso/al/file
```

- Confronta le versioni di più file tra il ramo corrente e un altro ramo:

```bash
git diff ramo:percorso/al/file2 percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | git-diff: remove 9th example (#4204) | 2020-07-23T05:06:21 | [0f879b604921](https://github.com/tldr-pages/tldr/commit/0f879b6049212a9e81396c345252a0a707f988d0)
[Marco Bonelli](mailto:marco@mebeim.net) | git-diff: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [ea4491c18f08](https://github.com/tldr-pages/tldr/commit/ea4491c18f08c0ae93b530cf00f9da133da77fcd)

