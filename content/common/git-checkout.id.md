---
author: ['Levi Rizki Saputra']
date: 1604236947
title: "git checkout"
description: "git checkout, Checkout cabang atau alamat ke direktori kerja."
categories: "common"
---
> Informasi lebih lanjut: <https://git-scm.com/docs/git-checkout>.

- Membuat dan beralih ke cabang baru:

```bash
git checkout -b nama_cabang
```

- Membuat dan beralih ke cabang baru berdasarkan referensi tertentu (misal cabang, remote, cabang remote, dan tag):

```bash
git checkout -b nama_cabang referense
```

- Beralih ke cabang lokal yang ada:

```bash
git checkout nama_cabang
```

- Beralih ke cabang yang sebelumnya di checkout:

```bash
git checkout -
```

- Beralih ke cabang remote yang ada:

```bash
git checkout --track nama_remote/nama_cabang
```

- Menyingkirkan semua perubahan yang tidak masuk status stage pada direktori saat ini (lihat `git reset` untuk perintah yang lebih mirip undo):

```bash
git checkout .
```

- Menyingkirkan perubahan yang tidak masuk status stage pada berkas:

```bash
git checkout nama_berkas
```

- Mengganti berkas pada direktori saat ini dengan versi pada cabang lain:

```bash
git checkout nama_cabang -- nama_berkas
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | git-checkout: add Indonesian translation | 2020-11-01T14:22:27 | [d5d8c3316735](https://github.com/tldr-pages/tldr/commit/d5d8c33167353053e75dac593e9e2e57cfa558aa)

