---
author: ['Levi Rizki Saputra']
date: 1603629602
title: "adb install, TLDR Pages"
description: "adb install, Android Debug Bridge Install: Menginstal paket ke emulator Android atau perangkat Android terhubung."
categories: "common"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb>.

- Menginstal aplikasi Android ke emulator/perangkat:

```bash
adb install alamat/ke/berkas.apk
```

- Menginstal ulang aplikasi yang sudah ada, menjaga datanya:

```bash
adb install -r alamat/ke/berkas.apk
```

- Memberikan semua izin yang terdaftar di manifest aplikasi:

```bash
adb install -g alamat/ke/berkas.apk
```

- Memperbarui langsung paket terinstal dengan hanya memperbarui bagian dari APK yang berubah:

```bash
Adb install --fastdeploy alamat/ke/berkas.apk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

