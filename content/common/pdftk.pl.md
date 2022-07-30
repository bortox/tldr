---
author: ['mrskizzex']
date: 1603544011
title: "pdftk"
description: "pdftk, Zestaw narzędzi PDF."
categories: "common"
---
> Więcej informacji: <https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit>.

- Wyodrębnij strony 1-3, 5 i 6-10 z pliku PDF oraz zapisz je jako inny plik PDF:

```bash
pdftk plik_wejściowy.pdf cat 1-3 5 6-10 output plik_wyjściowy.pdf
```

- Połącz listę plików PDF i zapisz połączony plik jako:

```bash
pdftk plik1.pdf plik2.pdf ... cat output plik_wyjściowy.pdf
```

- Podziel każdą stronę pliku PDF do osobnych plików, o nazwie nadanej według zdefiniowanego wzoru:

```bash
pdftk plik_wejściowy.pdf burst output plik_wyjściowy_%d.pdf
```

- Obróć wszystkie strony o 180 stopni zgodnie ze wskazówkami zegara:

```bash
pdftk plik_wejściowy.pdf cat 1-endsouth output plik_wyjściowy.pdf
```

- Obóć trzecią stronę o 90 stopni zgodnie ze wskazówkami zegara oraz pozostaw pozostałe strony bez zmian:

```bash
pdftk plik_wejściowy.pdf cat 1-2 3east 4-end output plik_wyjściowy.pdf
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[mrskizzex](mailto:drizztes@gmail.com) | pdftk: add Polish translation (#4804) | 2020-10-24T14:53:31 | [dc21f7bb9fb8](https://github.com/tldr-pages/tldr/commit/dc21f7bb9fb82e2be1156e84790d0461c7fd86ca)

