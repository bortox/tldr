---
author: ['Michal', 'lincc']
date: 1643487459
title: "rar, TLDR Pages"
description: "rar, Archiwizator RAR. Obsługuje wielotomowe archiwa, które mogą być opcjonalnie samorozpakowujące się."
categories: "common"
---
> Więcej informacji: <https://manned.org/rar>.

- Zarchiwizuj 1 lub więcej plików:

```bash
rar a sciezka/do/nazwa_archiwum.rar sciezka/do/plik1 sciezka/do/plik2 sciezka/do/plik3
```

- Zarchiwizuj katalog:

```bash
rar a sciezka/do/nazwa_archiwum.rar sciezka/do/katalog
```

- Podziel archiwum na części równej wielkości (50M):

```bash
rar a -v50M -R sciezka/do/nazwa_archiwum.rar sciezka/do/plik_lub_katalog
```

- Chroń hasło wynikowego archiwum:

```bash
rar a -phaslo sciezka/do/nazwa_archiwum.rar sciezka/do/plik_lub_katalog
```

- Szyfruj dane pliku i nagłówki za pomocą hasła:

```bash
rar a -hphaslo sciezka/do/nazwa_archiwum.rar sciezka/do/plik_lub_katalog
```

- Użyj określonego poziomu kompresji (0-5):

```bash
rar a -mpoziom_kompresji sciezka/do/nazwa_archiwum.rar sciezka/do/plik_lub_katalog
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Michal](mailto:mich.biesiada@gmail.com) | update rar updated | 2020-04-19T14:31:16 | [8df6f06fd69f](https://github.com/tldr-pages/tldr/commit/8df6f06fd69f59e6af0d51477b7fcf4ab8f72ad3)
[Michal](mailto:mich.biesiada@gmail.com) | update rar updated | 2020-04-19T14:31:16 | [eb39f72a8771](https://github.com/tldr-pages/tldr/commit/eb39f72a8771aaf7005e2d4ef17a2acd60d5a1af)
[Michal](mailto:mich.biesiada@gmail.com) | create rar.md initial | 2020-04-19T14:31:16 | [5c294786854e](https://github.com/tldr-pages/tldr/commit/5c294786854e91629c84b965488d3ca284a73498)

