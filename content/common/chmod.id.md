---
author: ['Reinhart Previano Koentjoro']
date: 1660423001
title: "chmod"
description: "chmod, Mengubah hak akses pengguna suatu file atau direktori."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/chmod>.

- Berikan pengguna pembuat file hak untuk mengeksekusinya (misal: sebagai script):

```bash
chmod u+x file
```

- Berikan hak kepada pengguna untuk membaca ([r]ead) dan menulis ([w]rite) suatu file atau direktori:

```bash
chmod u+rw jalan/menuju/file_atau_direktori
```

- Hentikan hak akses terhadap [g]rup untuk mengeksekusi suatu file:

```bash
chmod g-x jalan/menuju/file
```

- Berikan semua pengguna hak untuk membaca dan mengeksekusi suatu file:

```bash
chmod a+rx jalan/menuju/file
```

- Berikan hak-hak akses suatu file yang sama dari [g]rup kepada pengguna di luar grup ([o]thers):

```bash
chmod o=g jalan/menuju/file
```

- Hentikan semua hak akses suatu file:

```bash
chmod o= jalan/menuju/file
```

- Berikan hak tulis suatu direktori bagi [g]rup dan lainnya secara [R]ekursif (termasuk seluruh file yang terkandung di dalamnya):

```bash
chmod -R g+w,o+w jalan/menuju/direktori
```

- Berikan hak semua pengguna untuk membaca seluruh file dan mengeksekusi para sub-direktori dalam suatu direktori:

```bash
chmod -R a+rX jalan/menuju/direktori
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart@reinhart1010.id) | chmod: add Indonesian translation (#8298) | 2022-08-13T22:36:41 | [b20ead2a5c16](https://github.com/tldr-pages/tldr/commit/b20ead2a5c163ba0278df34f7dbd22663fc22308)

