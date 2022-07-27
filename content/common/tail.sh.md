---
author: ['bl-ue']
date: 1617492083
title: "tail, TLDR Pages"
description: "tail, Prikazuje krajnji deo datoteke."
categories: "common"
---
> Više informacija: <https://www.gnu.org/software/coreutils/tail>.

- Prikaži poslednjih 'broj' linija u datoteci:

```bash
tail -n broj datoteka
```

- Prikaži celu datoteku od linije 'broj':

```bash
tail -n +broj datoteka
```

- Prikaži poslednjih 'broj' bajtova u datoteci:

```bash
tail -c broj datoteka
```

- Čitaj datoteku sve do `Ctrl + C`:

```bash
tail -f datoteka
```

- Čitaj datoteku sve do `Ctrl + C`, čak i kad je datoteka rotirana:

```bash
tail -F datoteka
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | rename pages.hbs to pages.sh See @vladimyr's message: https://gitter.im/tldr-pages/tldr?at=60625b22cfd0b814ebac164d | 2021-04-04T01:21:23 | [db8da892632b](https://github.com/tldr-pages/tldr/commit/db8da892632baaebb5f5d0cef2f1941f09d0466e)

