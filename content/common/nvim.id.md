---
author: ['Levi Rizki Saputra', 'marchersimon']
date: 1620637392
title: "nvim, TLDR Pages"
description: "nvim, Neovim, teks editor programmer berbasis Vim, menyediakan beberapa mode untuk manipulasi teks berbeda jenis."
categories: "common"
---
> Tekan `i` masuk mode edit. `<Esc>` kembali ke mode normal, yang tidak mengizinkan penyisipan teks biasa.

> Informasi lebih lanjut: <https://neovim.io>.

- Membuka berkas:

```bash
nvim berkas
```

- Masuk ke mode pengeditan teks (insert mode):

```bash
<Esc>i
```

- Menyalin ("yank") atau memotong ("delete") baris saat ini (tempel itu dengan `P`):

```bash
<Esc>yy|dd
```

- Batalkan operasi terakhir:

```bash
<Esc>u
```

- Mencari sebuah pattern pada berkas (tekan `n`/`N` untuk pergi ke kecocokan berikutnya/sebelumnya):

```bash
<Esc>/pattern_pencarian<Enter>
```

- Melakukan penggantian ekspresi reguler pada seluruh berkas:

```bash
<Esc>:%s/ekspresi_reguler/pengganti/g<Enter>
```

- Menyimpan (write) berkas, dan keluar:

```bash
<Esc>:wq<Enter>
```

- Keluar tanpa menyimpan:

```bash
<Esc>:q!<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

