---
author: ['Bartłomiej Małańczuk']
date: 1635945272
title: "chown"
description: "chown, Zmienia właściciela i grupę właścicieli dla plików i katalogów."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/chown>.

- Zmień  właściciela pliku/katalogu:

```bash
chown użytkownik ścieżka/do/pliku_lub_katalogu
```

- Zmień właściciela i grupę właścicieli pliku/katalogu:

```bash
chown użytkownik:grupa ścieżka/do/pliku_lub_katalogu
```

- Rekursywnie zmień właściciela katalogu i jego zawartości:

```bash
chown -R użytkownik ścieżka/do/katalogu
```

- Zmień właściciela dowiązania symbolicznego:

```bash
chown -h użytkownik ścieżka/do/dowiązania_symbolicznego
```

- Zmień właściciela pliku/katalogu by był taki sam jak w pliku referencyjnym:

```bash
chown --reference=ścieżka/do/pliku_referencyjnego ścieżka/do/pliku_lub_katalogu
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Bartłomiej Małańczuk](mailto:bart.malanczuk@gmail.com) | chown: add Polish translation (#7343) | 2021-11-03T14:14:32 | [7cb2a84777b5](https://github.com/tldr-pages/tldr/commit/7cb2a84777b558d9c1b10cd0d1eeafb0d9634a41)

