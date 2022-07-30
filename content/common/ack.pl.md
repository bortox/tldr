---
author: ['Dawid Szymański', 'Bartłomiej Małańczuk', 'marchersimon']
date: 1634802947
title: "ack"
description: "ack, Narzędzie wyszukiwania, takie jak grep, zoptymalizowane dla programistów."
categories: "common"
---
> Zobacz też: `rg`, który jest znacznie szybszy.

> Więcej informacji: <https://beyondgrep.com/documentation>.

- Znajdź pliki zawierające ciąg znaków lub wyrażenie regularne rekurencyjnie w bieżącym katalogu:

```bash
ack "wzorzec"
```

- Szukaj na podstawie wzorca bez uwzględniania wielkości liter:

```bash
ack --ignore-case "wzorzec"
```

- Szukaj linii zawierających wzorzec, wyświetl wyłącznie pasujący tekst bez pozostałej zawartości linii:

```bash
ack -o "wzorzec"
```

- Ogranicz wyszukiwanie do plików wyłącznie określonego typu:

```bash
ack --type=ruby "wzorzec"
```

- Wyszukaj z pominięciem plików określonego typu:

```bash
ack --type=noruby "wzorzec"
```

- Policz całkowitą liczbę dopasowań:

```bash
ack --count --no-filename "wzorzec"
```

- Pokaż nazwy plików i liczbę dopasowań w każdym z nich:

```bash
ack --count --files-with-matches "wzorzec"
```

- Wypisz wszystkie możliwe wartości które mogą być użyte dla `--type`:

```bash
ack --help-types
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Bartłomiej Małańczuk](mailto:bart.malanczuk@gmail.com) | ack: update polish translation (#6997) | 2021-10-21T09:55:47 | [f91465c49a8a](https://github.com/tldr-pages/tldr/commit/f91465c49a8ad69843b95245d5e612ee6560a5bb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Dawid Szymański](mailto:mrszymeq@gmail.com) | ack: add Polish translation | 2020-10-05T16:01:03 | [b5616801a73f](https://github.com/tldr-pages/tldr/commit/b5616801a73fd5235e10cb337f7744baafdae2b4)

