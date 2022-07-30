---
author: ['Reinhart Previano Koentjoro', 'MarkusS', 'boberlabob', 'Patrice Denis', 'marchersimon']
date: 1641608133
title: "apt"
description: "apt, Debian und Ubuntu Paket Management Tool."
categories: "linux"
---
> Empfohlene Alternative zu `apt-get` seit Ubuntu 16.04.

> Weitere Informationen: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Aktualisiere die Liste der Paketquellen (es wird empfohlen, diesen Befehl zu Beginn auszuführen):

```bash
sudo apt update
```

- Suche nach einem Paket:

```bash
apt search paket
```

- Zeige Informationen über ein Paket:

```bash
apt show paket
```

- Installiere ein Paket oder aktualisiere es zur neusten Version:

```bash
sudo apt install paket
```

- Entferne ein Paket:

```bash
sudo apt remove paket
```

- Aktualisiere alle installierten Pakete auf die neueste Version:

```bash
sudo apt upgrade
```

- Liste alle Pakete auf:

```bash
apt list
```

- Liste alle installierten Pakete auf:

```bash
apt list --installed
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[boberlabob](mailto:tobias.portmann@pm.me) | apt: fix typo in German translation (#5899) | 2021-05-05T19:34:49 | [697787a183b3](https://github.com/tldr-pages/tldr/commit/697787a183b349082ce1a33fc8a24acb8c6f2018)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

