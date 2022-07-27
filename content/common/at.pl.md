---
author: ['bl-ue', 'Krzysztof Bociurko']
date: 1617130906
title: "at, TLDR Pages"
description: "at, Wykonuje polecenia o zadanym czasie."
categories: "common"
---
> Aby działać poprawnie wymaga działającego serwisu atd (lub atrun).

> Więcej informacji: <https://man.archlinux.org/man/at.1>.

- Wykonaj za 5 minut polecenie wprowadzone przy użyciu wejścia standardowego (aby zakończyć naciśnij `Ctrl + D`):

```bash
at now + 5 minutes
```

- Wykonaj o 10:00 rano polecenie podane z wejścia standardowego:

```bash
echo "./zrób_backup.sh" | at 1000
```

- Wykonaj polecenia z podanego pliku w najbliższy wtorek o 21:30:

```bash
at -f ścieżka/do/pliku 9:30 PM Tue
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | at, atq, atrm, batch: add Polish translation (#4887) | 2020-10-30T11:49:41 | [9a326df50591](https://github.com/tldr-pages/tldr/commit/9a326df50591b12b4be35cf04619cdb492724072)

