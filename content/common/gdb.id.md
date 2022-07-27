---
author: ['Senjaya']
date: 1646253869
title: "gdb, TLDR Pages"
description: "gdb, GNU Debugger."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/gdb>.

- Menjalankan debug pada sebuah berkas yang dapat dieksekusi:

```bash
gdb berkas_exe
```

- Menambahkan sebuah proses pada gdb:

```bash
gdb -p berkas_exe
```

- Menjalankan debug dengan berkas core:

```bash
gdb -c core berkas_exe
```

- Mengeksekusi perintah GDB pada saat dijanlakan:

```bash
gdb -ex "perintah" berkas_exe
```

- Menjalankan gdb dan melemparkan argumen pada berkas yang dieksekusi:

```bash
gdb --args berkas_exe argumen1 argumen2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Senjaya](mailto:amarpanjis@gmail.com) | bat, gdb: add Indonesian translation (#7745) | 2022-03-02T21:44:29 | [e684c95af0e3](https://github.com/tldr-pages/tldr/commit/e684c95af0e3a9e3ed63a581cd765030b84f0911)

