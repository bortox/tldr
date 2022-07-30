---
author: ['Dario Vladović', 'Levi Rizki Saputra', 'marchersimon']
date: 1617292466
title: "rm"
description: "rm, Menghapus berkas atau direktori."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/rm>.

- Menghapus berkas dari lokasi manapun:

```bash
rm alamat/ke/berkas alamat/ke/berkas/lainnya
```

- Menghapus direktori dan semua subdirektorinya secara rekursif:

```bash
rm -r alamat/ke/direktori
```

- Menghapus direktori secara paksa, tanpa meminta konfirmasi atau menampilkan pesan kesalahan:

```bash
rm -rf alamat/ke/direktori
```

- Menghapus banyak berkas secara interaktif, dengan meminta konfirmasi sebelum setiap penghapusan:

```bash
rm -i (beberapa)_berkas
```

- Menghapus berkas dengan mode verbose, mencetak pesan untuk setiap berkas yang terhapus:

```bash
rm -v alamat/ke/directori/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)

