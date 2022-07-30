---
author: ['MarkusS', 'Lucas Gabriel Schneider', 'FantasyCookie17', 'Patrice Denis', 'Daniel', 'marchersimon']
date: 1634914980
title: "apt-get"
description: "apt-get, Debian und Ubuntu Paket Management Tool."
categories: "linux"
---
> Suche mit `apt-cache` nach Paketen.

> Weitere Informationen: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Aktualisiere die Liste der Paketquellen (es wird empfohlen diesen Befehl zu Beginn auszuführen):

```bash
apt-get update
```

- Installiere ein Paket oder aktualisiere es zur neuesten Version:

```bash
apt-get install paket
```

- Entferne ein Paket:

```bash
apt-get remove paket
```

- Entferne ein Paket und die dazugehörigen Konfigurationen:

```bash
apt-get purge paket
```

- Aktualisiere alle Pakete auf die neueste Version:

```bash
apt-get upgrade
```

- Reinige das Repository

```bash
apt-get autoclean
```

- Entferne alle Pakete, die nicht mehr benötigt werden:

```bash
apt-get autoremove
```

- Aktualisiere alle Pakete (wie `upgrade`), aber entfernt alle obsoleten Pakete:

```bash
apt-get dist-upgrade
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | German pages: Change 'neuste' to 'neueste' (#5844) | 2021-04-28T10:57:14 | [48b7458c8559](https://github.com/tldr-pages/tldr/commit/48b7458c85594857653369e5e9941fe3961c79f0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

