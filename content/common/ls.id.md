---
author: ['Axel Navarro', 'Dario Vladović', 'Levi Rizki Saputra', 'marchersimon']
date: 1617292466
title: "ls"
description: "ls, Menampilkan daftar konten pada direktori."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/ls>.

- Menampilkan daftar berkas dengan satu item tiap baris:

```bash
ls -1
```

- Menampilkan daftar semua berkas, termasuk berkas tersembunyi:

```bash
ls -a
```

- Menampilkan daftar semua berkas, dengan akhiran `/` ditambahkan ke nama direktori:

```bash
ls -F
```

- Menampilkan daftar berformat panjang (menampilkan izin, kepemilikan, ukuran dan waktu modifikasi pada setiap berkas):

```bash
ls -la
```

- Menampilkan daftar berformat panjang dan ukuran ditampilkan menggunakan unit yang mudah dibaca manusia (KiB, MiB, GiB):

```bash
ls -lh
```

- Menampilkan daftar berformat panjang dan diurutkan berdasarkan ukuran (menurun):

```bash
ls -lS
```

- Menampilkan daftar berformat panjang dari semua berkas dan diurutkan berdasarkan tanggal modifikasi (terlama dulu):

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)

