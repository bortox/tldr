---
author: ['Levi Rizki Saputra']
date: 1635360904
title: "scoop bucket"
description: "scoop bucket, Mengelola bucket: Repository Git yang berisi berkas yang menjelaskan bagaimana scoop menginstall aplikasi."
categories: "windows"
---
> Jika Scoop tidak tahu dimana sebuah bucket terletak, lokasi repository harus ditentukan.

> Informasi lebih lanjut: <https://github.com/lukesampson/scoop/wiki/Buckets>.

- Menampilkan daftar semua bucket yang sedang digunakan:

```bash
scoop bucket list
```

- Menampilkan daftar semua bucket yang dikenal:

```bash
scoop bucket known
```

- Menambahkan bucket yang dikenal berdasarkan namanya:

```bash
scoop bucket add nama
```

- Menambahkan bucket yang tidak dikenal bersarkan nama dan URL repository Git:

```bash
scoop bucket add nama https://contoh.com/repository.git
```

- Menghapus bucket berdasarkan namanya:

```bash
scoop bucket rm nama
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | explorer, scoop, scoop-bucket: add Indonesian translation (#7103) | 2021-10-27T20:55:04 | [4d7c4499bf6a](https://github.com/tldr-pages/tldr/commit/4d7c4499bf6a6ea03ff3516e523a05b03774604e)

