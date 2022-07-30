---
author: ['Adinda Praditya']
date: 1633264933
title: "rvm"
description: "rvm, Alat untuk menginstal, mengatur dan bekerja dengan berbagai lingkungan Ruby."
categories: "common"
---
> Informasi lebih lanjut: <https://rvm.io>.

- Instal satu atau lebih versi Ruby (dipisah dengan spasi):

```bash
rvm install version(s)
```

- Menampilkan daftar versi-versi yang terinstal:

```bash
rvm list
```

- Menggunakan spesifik versi Ruby:

```bash
rvm use version
```

- Menyetel versi Ruby bawaan:

```bash
rvm --default use version
```

- Memperbarui versi Ruby:

```bash
rvm upgrade current_version new_version
```

- Menghapus versi Ruby dan menyimpan kode sumbernya:

```bash
rvm uninstall version
```

- Menghapus versi Ruby sekaligus kode sumbernya:

```bash
rvm remove version
```

- Menampilkan spesifik _dependencies_ untuk sistem operasi anda:

```bash
rvm requirements
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adinda Praditya](mailto:apraditya@gmail.com) | rvm: add Indonesian translation (#6710) | 2021-10-03T14:42:13 | [fcc2f3654738](https://github.com/tldr-pages/tldr/commit/fcc2f365473804136a0fdd4dc3c6662fab015a1a)

