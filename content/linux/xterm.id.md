---
author: ['Azrael JD']
date: 1643230914
title: "xterm, TLDR Pages"
description: "xterm, Emulator terminal untuk sistem window X."
categories: "linux"
---
> Informasi lebih lanjut: <https://manned.org/xterm>.

- Membuka terminal dengan judul `Example`:

```bash
xterm -T Example
```

- Membuka terminal dalam mode fullscreen:

```bash
xterm -fullscreen
```

- Membuka terminal dengan warna background biru tua dan warna foreground (warna font) kuning:

```bash
xterm -bg darkblue -fg yellow
```

- Membuka terminal dengan 100 karakter per baris dan 35 baris, di posisi layar x=200px, y=20px:

```bash
xterm -geometry 100x35+200+20
```

- Membuka terminal dengan font Serif dengan ukuran font sebesar 20:

```bash
xterm -fa 'Serif' -fs 20
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | xterm, st: add Indonesian translation (#7698) | 2022-01-26T22:01:54 | [6678cc9c046d](https://github.com/tldr-pages/tldr/commit/6678cc9c046d380355d895bfb67dde5a2ffdbc01)

