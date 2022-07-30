---
author: ['Levi Rizki Saputra', 'marchersimon']
date: 1633112881
title: "aapt"
description: "aapt, Alat Pemaketan Android Asset."
categories: "common"
---
> Menyusun dan memaketkan resource aplikasi Android.

> Informasi lebih lanjut: <https://elinux.org/Android_aapt>.

- Daftar berkas-berkas yang termuat dalam arsip APK:

```bash
aapt list alamat/ke/aplikasi.apk
```

- Menampilkan metadata aplikasi (versi, izin, dsb.):

```bash
aapt dump badging alamat/ke/aplikasi.apk
```

- Membuat arsip APK baru dengan berkas dari direktory yang ditentukan:

```bash
aapt package -F alamat/ke/aplikasi.apk alamat/ke/direktori
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

