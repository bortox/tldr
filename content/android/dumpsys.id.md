---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "dumpsys"
description: "dumpsys, Memberikan informasi tentang layanan (daemon) sistem milik Android."
categories: "android"
---
> Perintah ini hanya dapat dijalankan melalui `adb shell`.

> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/dumpsys>.

- Menampilkan informasi diagnostik terhadap seluruh layanan sistem Android:

```bash
dumpsys
```

- Menampilkan informasi diagnostik untuk layanan sistem tertentu:

```bash
dumpsys layanan
```

- Menampilkan daftar layanan sistem yang diketahui oleh `dumpsys`:

```bash
dumpsys -l
```

- Menampilkan daftar argumen yang diterima oleh sebuah layanan sistem:

```bash
dumpsys layanan -h
```

- Mengecualikan layanan sistem tertentu dari informasi diagnostik yang ditampilkan:

```bash
dumpsys --skip layanan
```

- Menetapkan periode waktu habis dalam hitungan detik (10 detik secara default):

```bash
dumpsys -t detik
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

