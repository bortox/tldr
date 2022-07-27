---
author: ['Krzysztof Bociurko']
date: 1635770573
title: "wc, TLDR Pages"
description: "wc, Zlicza linie, słowa, i bajty"
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/wc>.

- Policz linie w pliku

```bash
wc -l plik
```

- Policz słowa w pliku:

```bash
wc -w plik
```

- Policz znaki (bajty) w pliku:

```bash
wc -c plik
```

- Policz znaki w pliku (uwzględniając znaki zapisane więcej niż jednym bajtem):

```bash
wc -m plik
```

- Użyj standardowego wejścia aby policzyć po kolei linie, słowa, i znaki (bajty):

```bash
find . | wc
```

- Policz długość najdłuższej linii w pliku:

```bash
wc --max-line-length plik
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | w, wc, yes: add Polish translation (#7319) | 2021-11-01T13:42:53 | [8bfea7360429](https://github.com/tldr-pages/tldr/commit/8bfea736042993d24ecd736d7e384c3a069732e8)

