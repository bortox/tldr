---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "input, TLDR Pages"
description: "input, Mengirim sinyal input terhadap sebuah perangkat Android."
categories: "android"
---
> Perintah ini hanya dapat dijalankan melalui `adb shell`.

> Informasi lebih lanjut: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Memasukkan input karakter (layaknya pada papan kunci / keyboard) terhadap perangkat Android:

```bash
input keyevent kode_event
```

- Memasukkan input teks ke dalam perangkat Android (spasi ditandai dengan `%s`):

```bash
input text "teks"
```

- Memasukkan input sentuhan layar pada posisi tertentu:

```bash
input tap posisi_x posisi_y
```

- Mensimulasikan gerakan usap/swipe terhadap perangkat Android:

```bash
input swipe posisi_awal_x posisi_awal_y posisi_akhir_x posisi_akhir_y durasi_dalam_milidetik
```

- Mensimulasikan interaksi tekan-dan-tahan terhadap perangkat Android:

```bash
input swipe posisi_x posisi_y posisi_x posisi_y durasi_dalam_milidetik
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

