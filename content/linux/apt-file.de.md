---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "apt-file, TLDR Pages"
description: "apt-file, Suche nach Dateien in apt Paketen, auch in den nicht installierten."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Aktualisiere die Metadatenbank:

```bash
sudo apt update
```

- Suche nach Paketen, die die/den spezifizierten Pfad/Datei enthalten:

```bash
apt-file search|find pfad/zur/datei
```

- Liste die Inhalte eines bestimmten Pakets auf:

```bash
apt-file show|list paketname
```

- Suche nach Paketen auf die die Regular Expression zutrifft:

```bash
apt-file search|find --regexp regular_expression
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

