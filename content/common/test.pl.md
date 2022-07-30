---
author: ['Krzysztof Bociurko']
date: 1636246663
title: "test"
description: "test, Sprawdza typy plików i porównuje wartości."
categories: "common"
---
> Zwraca 0 gdy porównanie zwróciło wartość poprawną, 1 gdy fałszywą.

> Więcej informacji: <https://www.gnu.org/software/coreutils/test>.

- Sprawdź czy podana zmienna jest równa łańcuchowi znaków:

```bash
test "$ZMIENNA" == "/bin/zsh"
```

- Sprawdź czy zmienna jest pusta:

```bash
test -z "$GIT_BRANCH"
```

- Sprawdź czy plik istnieje:

```bash
test -f "ścieżka/do/pliku"
```

- Sprawdź czy katalog nie istnieje:

```bash
test ! -d "ścieżka/do/katalogu"
```

- Zapis jeśli porawne-jeśli fałszywe:

```bash
test warunek && echo "gdy poprawne" || echo "gdy fałszywe"
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | [, test: add Polish translation (#7354) | 2021-11-07T01:57:43 | [78b19eebc367](https://github.com/tldr-pages/tldr/commit/78b19eebc3677a1ae9890450708fff2a89f77ffa)

