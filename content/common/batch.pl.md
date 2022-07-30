---
author: ['bl-ue', 'marchersimon', 'Krzysztof Bociurko']
date: 1659075216
title: "batch, TLDR Pages"
description: "batch, Wykonaj polecenia, gdy pozwoli na to poziom obciążenia systmu."
categories: "common"
---
> Aby działać poprawnie wymaga działającego serwisu atd (lub atrun).

> Więcej informacji: <https://manned.org/batch>.

- Wykonaj polecenie wprowadzone przy użyciu wejścia standardowego (aby zakończyć naciśnij `Ctrl + D`):

```bash
batch
```

- Wykonaj polecenie podane z wejścia standardowego:

```bash
echo "./zrób_backup.sh" | batch
```

- Wykonaj polecenia z podanego pliku:

```bash
batch -f ścieżka/do/pliku
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | at, atq, atrm, batch: add Polish translation (#4887) | 2020-10-30T11:49:41 | [9a326df50591](https://github.com/tldr-pages/tldr/commit/9a326df50591b12b4be35cf04619cdb492724072)

