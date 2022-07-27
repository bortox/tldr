---
author: ['marchersimon', 'Austin', 'lincc']
date: 1636372515
title: "pacman, TLDR Pages"
description: "pacman, Arch Linux Paket Management Tool."
categories: "linux"
---
> Manche Unterbefehle wie `pacman sync` sind separat dokumentiert.

> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Synchronisiere und aktualisiere alle Pakete:

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Installiere ein neues Paket:

```bash
sudo pacman --sync paketname
```

- Entferne ein Paket und dessen Abhängigkeiten:

```bash
sudo pacman --remove --recursive paketname
```

- Suche in der Paketdatenbank nach einem regulären Ausdruck oder Schlüsselwort:

```bash
pacman --sync --search "suchmuster"
```

- Liste alle installierten Pakete und dessen Versionen auf:

```bash
pacman --query
```

- Liste alle ausdrücklich installierten Pakete und dessen Versionen auf:

```bash
pacman --query --explicit
```

- Zeige verwaiste Pakete an, welche als Abhängigkeiten installiert wurden, aber nicht mehr von anderen Paketen benötigt werden.

```bash
pacman --query --unrequired --deps --quiet
```

- Leere den gesamten pacman Cache:

```bash
sudo pacman --sync --clean --clean
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman: add German translation (#6757) | 2021-10-05T19:40:41 | [be89607986c4](https://github.com/tldr-pages/tldr/commit/be89607986c4cf68e17b7a04a9ef9ede34044657)

