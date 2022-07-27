---
author: ['Dario Vladović', 'Dewa Widyakumara', 'marchersimon']
date: 1617292466
title: "touch, TLDR Pages"
description: "touch, Mengubah waktu akses (atime) dan waktu modifikasi (mtime) dari sebuah file."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/touch>.

- Membuat file baru yang kosong atau mengubah waktu file yang telahj ada ke waktu sekarang:

```bash
touch nama_file
```

- Mengatur waktu sebuah file ke tanggal dan jam tertentu:

```bash
touch -t YYYYMMDDHHMM.SS nama_file
```

- Menggunakan waktu dari satu file untuk mengatur waktu file yang lain:

```bash
touch -r nama_file nama_file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Dewa Widyakumara](mailto:widyakumara@users.noreply.github.com) | alias, cp, mkdir, mv, touch: add Indonesian translation (#4697) | 2020-10-19T17:58:29 | [63bd53ed59ca](https://github.com/tldr-pages/tldr/commit/63bd53ed59cac2bfe8bc5094821d509a094fe19d)

