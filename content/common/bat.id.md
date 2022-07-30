---
author: ['Senjaya']
date: 1646253869
title: "bat"
description: "bat, Mencetak dan menggabungkan berkas."
categories: "common"
---
> klon dari `cat` dengan sintaks berwarna dan integrasi Git.

> Informasi lebih lanjut: <https://github.com/sharkdp/bat>.

- Mencetak konten berkas ke keluaran standar:

```bash
bat berkas
```

- Menggabungkan konten beberapa berkas ke berkas tujuan:

```bash
bat berkas1 berkas2 > berkas_tujuan
```

- Menambahkan konten beberapa berkas ke berkas tujuan:

```bash
bat berkas1 berkas2 >> berkas_tujuan
```

- Memberi nomor pada setiap baris keluaran:

```bash
bat -n berkas
```

- Mencetak konten JSON dengan sintaks berwarna:

```bash
bat --language json berkas.json
```

- Menampilkan semua bahasa yang didukung:

```bash
bat --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Senjaya](mailto:amarpanjis@gmail.com) | bat, gdb: add Indonesian translation (#7745) | 2022-03-02T21:44:29 | [e684c95af0e3](https://github.com/tldr-pages/tldr/commit/e684c95af0e3a9e3ed63a581cd765030b84f0911)

