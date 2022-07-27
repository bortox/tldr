---
author: ['Levi Rizki Saputra', 'marchersimon']
date: 1631521281
title: "adb, TLDR Pages"
description: "adb, Android Debug Bridge: berkomunikasi dengan emulator Android atau perangkat Android terhubung."
categories: "common"
---
> Kami mempunyai dokumentasi terpisah untuk menggunakan subperintah seperti `adb shell`.

> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb>.

- Cek apakah proses server adb telah dimulai dan memulainya:

```bash
adb start-server
```

- Menghentikan proses server adb:

```bash
adb kill-server
```

- Memulai shell jarak jauh pada emulator/perangkat tujuan:

```bash
adb shell
```

- Menginstal aplikasi Android ke emulator/perangkat tujuan:

```bash
adb install -r alamat/ke/berkas.apk
```

- Menyalin berkas/direktori dari perangkat tujuan:

```bash
adb pull alamat/ke/berkas_atau_direktori_perangkat alamat/ke/direktori_lokal_tujuan
```

- Menyalin berkas/direktori ke perangkat tujuan:

```bash
adb push alamat/ke/berkas_atau_direktori_lokal alamat/ke/direktori_perangkat_tujuan
```

- Mendapatkan daftar perangkat yang terhubung:

```bash
adb devices
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

