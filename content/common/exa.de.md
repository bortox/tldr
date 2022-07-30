---
author: ['Frank Benedikt', 'bl-ue', 'marchersimon']
date: 1626631245
title: "exa"
description: "exa, Ein moderner Ersatz für `ls` (Verzeichnisinhalte auflisten)."
categories: "common"
---
> Weitere Informationen: <https://the.exa.website>.

- Liste eine Datei pro Zeile auf:

```bash
exa --oneline
```

- Liste alle Dateien auf, einschließlich versteckter Dateien:

```bash
exa --all
```

- Liste alle Dateien im langen Format auf (Berechtigungen, Eigentümer, Größe und Änderungsdatum):

```bash
exa --long --all
```

- Liste Dateien nach Größe absteigend sortiert auf:

```bash
exa --reverse --sort=size
```

- Zeige Dateien in einer Baumstruktur an, die drei Ebenen tief ist:

```bash
exa --long --tree --level=3
```

- Liste Dateien nach Änderungsdatum aufsteigend sortiert auf:

```bash
exa --long --sort=modified
```

- Liste Dateien inklusive Header, Icons und Git-Status:

```bash
exa --long --header --icons --git
```

- Liste keine Dateien auf, die in `.gitignore` erwähnt werden:

```bash
exa --git-ignore
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

