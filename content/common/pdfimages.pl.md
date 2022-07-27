---
author: ['mrskizzex', 'lincc']
date: 1643487459
title: "pdfimages, TLDR Pages"
description: "pdfimages, Narzędzie do wyodrębniania obrazów z plików PDF."
categories: "common"
---
> Więcej informacji: <https://manned.org/pdfimages>.

- Wyodrębnij wszystkie obrazy z pliku PDF i zapisz je jako pliki PNG:

```bash
pdfimages -png ścieżka/do/pliku.pdf przedrostek_nazwy_pliku
```

- Wyodrębnij obrazy ze stron 3 do 5:

```bash
pdfimages -f 3 -l 5 ścieżka/do/pliku.pdf przedrostek_nazwy_pliku
```

- Wyodrębnij obrazy z pliku PDF oraz zawrzyj numer strony w nazwach wyjściowych:

```bash
pdfimages -p ścieżka/do/pliku.pdf przedrostek_nazwy_pliku
```

- Wyświetl listę informacji o każdym obrazie w pliku PDF:

```bash
pdfimages -list ścieżka/do/pliku.pdf
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[mrskizzex](mailto:drizztes@gmail.com) | pdfimages: add Polish translation (#4808) | 2020-10-24T14:54:58 | [8d01930668cf](https://github.com/tldr-pages/tldr/commit/8d01930668cfcd61e4ff1ac0a3bc08a11e384bbb)

