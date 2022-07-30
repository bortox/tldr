---
author: ['Dario Vladović', 'Lucas Gabriel Schneider', 'b3nj4m1n', 'marchersimon']
date: 1619262596
title: "cut"
description: "cut, Schneide Felder von stdin oder einer Datei aus."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/cut>.

- Schneide die ersten 16 Zeichen jeder Zeile von stdin aus:

```bash
cut -c 1-16
```

- Schneide die ersten 16 Zeichen jeder Zeile der angegebenen Datei aus:

```bash
cut -c 1-16 pfad/zu/datei
```

- Schneide alles ab dem dritten Zeichen bis zum Ende der Zeile aus:

```bash
cut -c 3-
```

- Schneide das fünfte Feld jeder Zeile aus und nutze den Doppelpunkt als Trennzeichen (standardmäßig Tab):

```bash
cut -d':' -f5
```

- Schneide das 2. und 10. Feld jeder Zeile aus und nutze Semikolon als Trennzeichen:

```bash
cut -d';' -f2,10
```

- Schneide alles ab dem dritten Zeichen bis zum Ende der Zeile aus und nutze Leerzeichen als Trennzeichen:

```bash
cut -d' ' -f3-
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cut: add link (#5576) | 2021-03-30T13:39:27 | [f311aa47f394](https://github.com/tldr-pages/tldr/commit/f311aa47f394998f831ebd4af66733b85cc9c08a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | cut: add German translation | 2020-07-02T17:41:08 | [6724ba3af39d](https://github.com/tldr-pages/tldr/commit/6724ba3af39dd0cf4ccf41c81f53b02daa6d9b17)

