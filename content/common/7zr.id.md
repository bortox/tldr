---
author: ['trolzen', 'Reinhart Previano Koentjoro']
date: 1634589976
title: "7zr"
description: "7zr, Pengarsip file dengan rasio kompresi yang tinggi."
categories: "common"
---
> Serupa dengan `7z` namun mendukung format file arsip `.7z` saja.

> Informasi lebih lanjut: <https://www.7-zip.org>.

- Meng[a]rsipkan sebuah file atau direktori:

```bash
7zr a jalan/menuju/arsip.7z jalan/menuju/file_atau_direktori
```

- Mengenkripsi sebuah file arsip (termasuk nama-nama file yang terkandung di dalamnya):

```bash
7zr a jalan/menuju/arsip_terenkripsi.7z -pkata sandi -mhe=on jalan/menuju/arsip.7z
```

- Mengekstrak sebuah file arsip dengan mempertahankan struktur direktori asli:

```bash
7zr x jalan/menuju/arsip.7z
```

- Mengekstrak sebuah file arsip ke dalam direktori yang ditentukan:

```bash
7zr x jalan/menuju/arsip.7z -ojalan/menuju/direktori
```

- Mengekstrak sebuah file arsip menuju stdout:

```bash
7zr x jalan/menuju/arsip.7z -so
```

- Me[l]ihat daftar isi dari sebuah file arsip:

```bash
7zr l jalan/menuju/arsip.7z
```

- Mengetahui daftar format file arsip yang didukung:

```bash
7zr i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[trolzen](mailto:trolzen@gmail.com) | 7z*: sync German and Indonesian translation (#7093) | 2021-10-18T22:46:16 | [49161f33794b](https://github.com/tldr-pages/tldr/commit/49161f33794b7359ec6d28bd8773248f81854fd0)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | 7z, 7za, 7zr: add Indonesian translation (#6061) | 2021-05-28T21:02:42 | [c7d686427afd](https://github.com/tldr-pages/tldr/commit/c7d686427afdc48390d5e7f7b8de4f2a0a001e20)

