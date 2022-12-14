---
author: ['trolzen', 'Reinhart Previano Koentjoro']
date: 1634591417
title: "7za"
description: "7za, Pengarsip file dengan rasio kompresi yang tinggi."
categories: "common"
---
> Serupa dengan `7z` namun mendukung lebih sedikit format file arsip dan dapat digunakan lintas sistem operasi.

> Informasi lebih lanjut: <https://www.7-zip.org>.

- Meng[a]rsipkan sebuah file atau direktori:

```bash
7za a jalan/menuju/arsip.7z jalan/menuju/file_atau_direktori
```

- Mengenkripsi sebuah file arsip (termasuk nama-nama file yang terkandung di dalamnya):

```bash
7za a jalan/menuju/arsip_terenkripsi.7z -pkata sandi -mhe=on jalan/menuju/arsip.7z
```

- Mengekstrak sebuah file arsip dengan mempertahankan struktur direktori asli:

```bash
7za x jalan/menuju/arsip.7z
```

- Mengekstrak sebuah file arsip ke dalam direktori yang ditentukan:

```bash
7za x jalan/menuju/arsip.7z -ojalan/menuju/direktori
```

- Mengekstrak sebuah file arsip menuju stdout:

```bash
7za x jalan/menuju/arsip.7z -so
```

- Meng[a]rsipkan file atau direktori menggunakan format file arsip tertentu:

```bash
7za a -t7z|bzip2|gzip|lzip|tar|zip jalan/menuju/arsip.7z jalan/menuju/file_atau_direktori
```

- Me[l]ihat daftar isi dari sebuah file arsip:

```bash
7za l jalan/menuju/arsip.7z
```

- Mengetahui daftar format file arsip yang didukung:

```bash
7za i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[trolzen](mailto:trolzen@gmail.com) | 7z, 7za, 7zr: update list of archive formats (#7079) | 2021-10-18T23:10:17 | [1c07b17a6c31](https://github.com/tldr-pages/tldr/commit/1c07b17a6c319eb4d72fd840ee479565893bc3f1)
[trolzen](mailto:trolzen@gmail.com) | 7z*: sync German and Indonesian translation (#7093) | 2021-10-18T22:46:16 | [49161f33794b](https://github.com/tldr-pages/tldr/commit/49161f33794b7359ec6d28bd8773248f81854fd0)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | 7z, 7za, 7zr: add Indonesian translation (#6061) | 2021-05-28T21:02:42 | [c7d686427afd](https://github.com/tldr-pages/tldr/commit/c7d686427afdc48390d5e7f7b8de4f2a0a001e20)

