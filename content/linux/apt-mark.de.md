---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "apt-mark, TLDR Pages"
description: "apt-mark, Tool um den Status eines installierten Paketes zu verändern."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Markiere ein Paket als automatisch installiert:

```bash
sudo apt-mark auto paketname
```

- Halte ein Paket auf seiner aktuellen Version und verhindere dass es aktualisiert wird:

```bash
sudo apt-mark hold paketname
```

- Erlaube dass ein Paket wieder aktualisiert werden darf:

```bash
sudo apt-mark unhold paketname
```

- Zeige manuell installierte Pakete:

```bash
apt-mark showmanual
```

- Zeige gehaltene Pakete die nicht aktualisiert werden dürfen:

```bash
apt-mark showhold
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

