---
author: ['Levi Rizki Saputra']
date: 1604241432
title: "hugo, TLDR Pages"
description: "hugo, Penghasil website statis berbasis template. Menggunakan modul, komponen dan tema."
categories: "common"
---
> Informasi lebih lanjut: <https://gohugo.io>.

- Membuat website Hugo baru:

```bash
hugo new site alamat/ke/website
```

- Membuat tema Hugo baru (tema juga dapat diunduh dari https://themes.gohugo.io/):

```bash
hugo new theme nama_tema
```

- Membuat halaman baru:

```bash
hugo new nama_bagian/nama_berkas
```

- Menbuild website ke direktori `./public`:

```bash
hugo
```

- Menbuild website termasuk halaman yang ditandai sebagai "draft":

```bash
hugo --buildDrafts
```

- Menbuild website ke direktori yang ditentukan:

```bash
hugo --destination alamat/tujuan
```

- Menbuild website, memulai webserver untuk menyajikannya, dan secara otomatis memuat ulang jika ada halaman yang berubah:

```bash
hugo server
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)

