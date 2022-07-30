---
author: ['Dario Vladović', 'mrskizzex', 'marchersimon']
date: 1617292466
title: "pathchk"
description: "pathchk, Sprawdź poprawność oraz przenośność jednej lub większej ilości ścieżek."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/pathchk>.

- Sprawdź ścieżki pod kątem poprawności w obecnym systemie:

```bash
pathchk ścieżka1 ścieżka2 …
```

- Sprawdź ścieżki pod kątem poprawności w szerszym zakresie systemów zgodnych z POSIX:

```bash
pathchk -p ścieżka1 ścieżka2 …
```

- Sprawdź ścieżki pod kątem poprawności we wszystkich systemach zgodnych z POSIX:

```bash
pathchk --portability ścieżka1 ścieżka2 …
```

- Sprawdź tylko pod kątem pustych ścieżek lub wiodących myślników (-):

```bash
pathchk -P ścieżka1 ścieżka2 …
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pathchk: add more information link (#5619) | 2021-03-30T16:13:36 | [6d3765b2d869](https://github.com/tldr-pages/tldr/commit/6d3765b2d869b3b0b0237cad5594d75b38de3f46)
[mrskizzex](mailto:drizztes@gmail.com) | pathchk: add Polish translation (#4807) | 2020-10-24T14:54:22 | [442f2306e59e](https://github.com/tldr-pages/tldr/commit/442f2306e59e457d646e9a3d533997cb3c4d44e1)

