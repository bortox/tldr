---
author: ['marchersimon', 'lincc', 'Austin']
date: 1660133637
title: "pacman"
description: "pacman, Arch Linux Paket Management Tool."
categories: "linux"
---
> Manche Unterbefehle wie `pacman sync` sind separat dokumentiert.

> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Synchronisiere und aktualisiere alle Pakete:

```bash
sudo pacman -Syu
```

- Installiere ein neues Paket:

```bash
sudo pacman -S paketname
```

- Entferne ein Paket und dessen Abhängigkeiten:

```bash
sudo pacman -Rs paketname
```

- Suche in der Paketdatenbank nach einem regulären Ausdruck oder Schlüsselwort:

```bash
pacman -Ss "suchmuster"
```

- Liste alle installierten Pakete und dessen Versionen auf:

```bash
pacman -Q
```

- Liste alle ausdrücklich installierten Pakete und dessen Versionen auf:

```bash
pacman -Qe
```

- Zeige verwaiste Pakete an, welche als Abhängigkeiten installiert wurden, aber nicht mehr von anderen Paketen benötigt werden.

```bash
pacman -Qtdq
```

- Leere den gesamten pacman Cache:

```bash
sudo pacman -Scc
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: use short options only (#8286) | 2022-08-10T14:13:57 | [1f147d6b91a6](https://github.com/tldr-pages/tldr/commit/1f147d6b91a67044e5f60817a0355d2acd40bb88)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman: add German translation (#6757) | 2021-10-05T19:40:41 | [be89607986c4](https://github.com/tldr-pages/tldr/commit/be89607986c4cf68e17b7a04a9ef9ede34044657)

