---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "diff, TLDR Pages"
description: "diff, Confronta file e directory."
categories: "common"
---
> Maggiori informazioni: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Confronta due file (elenca cambiamenti necessari per trasformare `vecchio_file` in `nuovo_file`):

```bash
diff vecchio_file nuovo_file
```

- Confronta due file ignorando gli spazi:

```bash
diff -w vecchio_file nuovo_file
```

- Confronta due file mostrando le differenze fianco a fianco:

```bash
diff -y vecchio_file nuovo_file
```

- Confronta due file, mostrando le differenze in formato unificato (come `git diff`):

```bash
diff -u vecchio_file nuovo_file
```

- Confronta due directory ricorsivamente (mostra i nomi dei file/directory diversi e le differenze trai file):

```bash
diff -r old_directory new_directory
```

- Confronta due directory mostrando solamente il nome dei file diversi:

```bash
diff -rq old_directory new_directory
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | diff: add Italian translation. | 2019-07-21T01:59:28 | [4590a0263e62](https://github.com/tldr-pages/tldr/commit/4590a0263e6290cbef48489d2a6db00827818d24)

