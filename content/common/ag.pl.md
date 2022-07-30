---
author: ['Dawid Lemieszek']
date: 1601906463
title: "ag"
description: "ag, The Silver Searcher. Podobny do ack, ale ma być szybszy."
categories: "common"
---
> Więcej informacji: <https://github.com/ggreer/the_silver_searcher>.

- Znajdź pliki zawierające „foo” i wypisz dopasowane linie:

```bash
ag foo
```

- Znajdź pliki zawierające „foo” w określonym katalogu:

```bash
ag foo scieżka/do/katalogu
```

- Znajdź pliki zawierające „foo”, ale podaj tylko nazwy plików:

```bash
ag -l foo
```

- Znajdź pliki zawierające „FOO” bez rozróżniania wielkości liter i wypisz tylko dopasowanie, a nie całą linię:

```bash
ag -i -o FOO
```

- Znajdź „foo” w plikach o nazwie pasującej do „bar”:

```bash
ag foo -G bar
```

- Znajdź pliki, których zawartość pasuje do wyrażenia regularnego:

```bash
ag '^ba(r|z)$'
```

- Znajdź pliki o nazwie pasującej do „foo”:

```bash
ag -g foo
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dawid Lemieszek](mailto:mrszymeq@gmail.com) | ag: add Polish translation | 2020-10-05T16:01:03 | [226aad06ae38](https://github.com/tldr-pages/tldr/commit/226aad06ae3825de94ff04e9ef021c371ea777d2)

