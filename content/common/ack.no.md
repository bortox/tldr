---
author: ['JoeStone13']
date: 1635603369
title: "ack, TLDR Pages"
description: "ack, Et søkeverktøy som grep, optimalisert for utviklere."
categories: "common"
---
> Se også: `rg`, som er mye raskere.

> Mer informasjon: <https://beyondgrep.com/documentation>.

- Søk etter filer som inneholder en streng eller regulært uttrykk i gjeldende katalog rekursivt:

```bash
ack "søkemønster"
```

- Søk etter et mønster som ikke skiller mellom store og små bokstaver:

```bash
ack --ignore-case "søkemønster"
```

- Søk etter linjer som samsvarer med et mønster, skriv ut bare den samsvarende teksten og ikke resten av linjen:

```bash
ack -o "søkemønster"
```

- Begrens søket til filer av en bestemt type:

```bash
ack --type=ruby "søkemønster"
```

- Ikke søk i filer av en bestemt type:

```bash
ack --type=noruby "søkemønster"
```

- Tell totalt antall treff funnet:

```bash
ack --count --no-filename "søkemønster"
```

- Skriv ut filnavnene og antall treff kun for hver fil:

```bash
ack --count --files-with-matches "søkemønster"
```

- List opp alle verdiene som kan brukes med  `--type`:

```bash
ack --help-types
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JoeStone13](mailto:captainjoestone@gmail.com) | ack: add Norwegian translation (#7293) | 2021-10-30T16:16:09 | [55e8e61a6fb5](https://github.com/tldr-pages/tldr/commit/55e8e61a6fb5bf1d125bf834c96e6279b3a4f1ed)

