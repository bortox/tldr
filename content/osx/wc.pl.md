---
author: ['Krzysztof Bociurko', 'marchersimon']
date: 1659075216
title: "wc"
description: "wc, Zlicza linie, słowa, i bajty"
categories: "osx"
---
> Więcej informacji: <https://ss64.com/osx/wc.html>.

- Policz linie w pliku

```bash
wc -l ścieżka/do/pliku
```

- Policz słowa w pliku:

```bash
wc -w ścieżka/do/pliku
```

- Policz znaki (bajty) w pliku:

```bash
wc -c ścieżka/do/pliku
```

- Policz znaki w pliku (uwzględniając znaki zapisane więcej niż jednym bajtem):

```bash
wc -m ścieżka/do/pliku
```

- Użyj standardowego wejścia aby policzyć po kolei linie, słowa, i znaki (bajty):

```bash
find . | wc
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | w, wc: add Polish translation (#7327) | 2021-11-04T11:06:14 | [8fa4693fbac0](https://github.com/tldr-pages/tldr/commit/8fa4693fbac038dc16c8ed23f5006912abea7ee3)

