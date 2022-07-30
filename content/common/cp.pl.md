---
author: ['Bartłomiej Małańczuk']
date: 1635829971
title: "cp"
description: "cp, Kopiuje pliki i katalogi."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/cp>.

- Kopiuj plik do innej lokalizacji:

```bash
cp ścieżka/do/pliku_źródłowego.ext ścieżka/do/pliku_docelowego.ext
```

- Kopiuj plik do innego katalogu, zachowując nazwę pliku:

```bash
cp ścieżka/do/pliku_źródłowego ścieżka/do/katalogu
```

- Kopiuj rekursywnie katalog z zawartością do innej lokalizacji (jeśli docelowa lokalizacja istnieje, katalog jest kopiowany do jej środka):

```bash
cp -R ścieżka/do/katalogu_źródłowego ścieżka/do/katalogu_docelowego
```

- Kopiuj katalog rekursywnie, w trybie opisowym (pokazuje pliki które zostały skopiowane):

```bash
cp -vR ścieżka/do/katalogu_źródłowego ścieżka/do/katalogu_docelowego
```

- Kopiuj pliki tekstowe do innej lokalizacji, w trybie interaktywnym (wyświetla pytanie o potwierdzenie przed nadpisywaniem):

```bash
cp -i *.txt ścieżka/do/katalogu_docelowego
```

- Podążaj za dowiązaniami symbolicznymi przed kopiowaniem:

```bash
cp -L dowiązanie ścieżka/do/katalogu_docelowego
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Bartłomiej Małańczuk](mailto:bart.malanczuk@gmail.com) | cp: add Polish translation (#7342) | 2021-11-02T06:12:51 | [7ea8fd0383dc](https://github.com/tldr-pages/tldr/commit/7ea8fd0383dc7872f8134f63d9cf8232aa377379)

