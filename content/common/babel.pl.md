---
author: ['Lucas Gabriel Schneider', 'Michal']
date: 1612112718
title: "babel, TLDR Pages"
description: "babel, Transpiler, który konwertuje kod ze składni JavaScript ES6 / ES7 na składnię ES5."
categories: "common"
---
> Więcej informacji: <https://babeljs.io/>.

- Transpiluj określony plik wejściowy i dane wyjściowe do stdout:

```bash
babel siezka/do/pliku
```

- Transpiluj określony plik wejściowy i wyjście do określonego pliku:

```bash
babel sciezka/do/pliku_wejsciowego --out-file sciezka/do/pliku_wyjsciowego
```

- Transpiluj plik wejściowy przy każdej zmianie:

```bash
babel sciezka/do/pliku_wejsciowego --watch
```

- Transpiluj cały katalog plików:

```bash
babel sciezka/do/katalogu_wejsciowego
```

- Zignoruj określone pliki oddzielone przecinkami w katalogu:

```bash
babel sciezka/do/katalogu_wejsciowego --ignore ignorowane_pliki
```

- Transpiluj i wypisz jako zminimalizowany JavaScript:

```bash
babel sciezka/do/pliku_wejsciowego --minified
```

- Wybierz zestaw ustawień dla formatowania wyjściowego:

```bash
babel sciezka/do/pliku_wejsciowego --presets presets
```

- Wyświetl wszystkie dostępne opcje:

```bash
babel --help
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michal](mailto:mich.biesiada@gmail.com) | update babel updated | 2020-04-19T14:31:16 | [f4faac72d23c](https://github.com/tldr-pages/tldr/commit/f4faac72d23c9cc4291f9c13d9639935da072d04)
[Michal](mailto:mich.biesiada@gmail.com) | update babel updated | 2020-04-19T14:31:16 | [df59ef8b9ae8](https://github.com/tldr-pages/tldr/commit/df59ef8b9ae8917e29b7d075498eb30f3a15c914)
[Michal](mailto:mich.biesiada@gmail.com) | create babel.md initial | 2020-04-19T14:31:16 | [d0f7e7e1d1e7](https://github.com/tldr-pages/tldr/commit/d0f7e7e1d1e778e4657ce25111f3d9c11b787fc8)

