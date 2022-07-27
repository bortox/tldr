---
author: ['Adinda Praditya', 'lincc']
date: 1643487459
title: "ps, TLDR Pages"
description: "ps, Informasi tentang proses-proses yang berlangsung."
categories: "common"
---
> Informasi lebih lanjut: <https://manned.org/ps>.

- Menampilkan daftar semua proses yang berlangsung:

```bash
ps aux
```

- Menampilkan daftar semua proses yang berlangsung termasuk _string_ perintah secara utuh:

```bash
ps auxww
```

- Mencari proses yang sesuai dengan _string_:

```bash
ps aux | grep string
```

- Menampilkan daftar semua proses pengguna yang berlangsung dengan format tambahan yang utuh:

```bash
ps --user $(id -u) -F
```

- Menampilkan daftar semua proses pengguna yang berlangsung sebagai pohon:

```bash
ps --user $(id -u) f
```

- Mengambil induk PID dari sebuah proses:

```bash
ps -o ppid= -p pid
```

- Sortir proses berdasarkan konsumsi memori:

```bash
ps --sort size
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Adinda Praditya](mailto:apraditya@gmail.com) | ps: add Indonesian translation (#6702) | 2021-10-03T15:17:56 | [4427cbcab83a](https://github.com/tldr-pages/tldr/commit/4427cbcab83a680ad82f0b5212cfa8dab4522253)

