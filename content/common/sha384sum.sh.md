---
author: ['bl-ue']
date: 1617492083
title: "sha384sum"
description: "sha384sum, Izračunava SHA384 kriptografske kontrolne brojeve."
categories: "common"
---
> Više informacija: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Izračunaj SHA384 kontrolni broj za datoteku:

```bash
sha384sum datoteka1
```

- Izračunaj SHA384 kontrolne brojeve za više datoteka:

```bash
sha384sum datoteka1 datoteka2
```

- Pročitaj datoteku SHA384 brojeva i proveri da li se svi kontrolni brojevi datoteka poklapaju:

```bash
sha384sum -c datoteka.sha384
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | rename pages.hbs to pages.sh See @vladimyr's message: https://gitter.im/tldr-pages/tldr?at=60625b22cfd0b814ebac164d | 2021-04-04T01:21:23 | [db8da892632b](https://github.com/tldr-pages/tldr/commit/db8da892632baaebb5f5d0cef2f1941f09d0466e)

