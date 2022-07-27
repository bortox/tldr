---
author: ['Dawid Szymański', 'marchersimon']
date: 1633112881
title: "7za, TLDR Pages"
description: "7za, Archiwizator plików o wysokim współczynniku kompresji."
categories: "common"
---
> Samodzielna wersja `7z` z obsługą mniejszej liczby typów archiwów.

> Więcej informacji: <https://www.7-zip.org>.

- Zarchiwizuj plik lub katalog:

```bash
7za a archiwum.7z scieżka/do/pliku_lub_katalogu
```

- Wyodrębnij istniejący plik 7z z oryginalną strukturą katalogów:

```bash
7za x archiwum
```

- Zarchiwizuj przy użyciu określonego typu archiwum:

```bash
7za a -tzip|gzip|bzip2|tar archiwum scieżka/do/pliku_lub_katalogu
```

- Wypisz dostępe typy archiwów:

```bash
7za i
```

- Wypisz zawartość pliku archiwum:

```bash
7za l archiwum
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Dawid Szymański](mailto:mrszymeq@gmail.com) | 7za: add Polish translation | 2020-10-05T16:01:03 | [b5440175e62a](https://github.com/tldr-pages/tldr/commit/b5440175e62ae30bb48fe98cf9281859bdbd937d)

