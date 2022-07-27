---
author: ['Dario Vladović', 'Levi Rizki Saputra', 'marchersimon']
date: 1617292466
title: "cat, TLDR Pages"
description: "cat, Mencetak dan menggabungkan berkas."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/cat>.

- Mencetak konten berkas ke keluaran standar:

```bash
cat berkas
```

- Menggabungkan konten beberapa berkas ke berkas tujuan:

```bash
cat berkas1 berkasw > berkas_tujuan
```

- Menambahkan konten beberapa berkas ke berkas tujuan:

```bash
cat berkas1 berkas2 >> berkas_tujuan
```

- Memberi nomor pada semua baris keluaran:

```bash
cat -n berkas
```

- Menampilkan karakter yang tidak dapat dicetak dan spasi (dengan awalan `M-`jika non-ASCII):

```bash
cat -v -t -e berkas
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | cat: Add indonesian translation | 2020-11-01T14:22:27 | [e22393ab6a0e](https://github.com/tldr-pages/tldr/commit/e22393ab6a0ee9fa57697d95223bd93a1e4135bf)

