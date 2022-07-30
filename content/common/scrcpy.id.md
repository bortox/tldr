---
author: ['Reinhart Previano Koentjoro']
date: 1622155662
title: "scrcpy"
description: "scrcpy, Tampilkan layar and kontrol perangkat Android anda di dalam desktop."
categories: "common"
---
> Informasi lebih lanjut: <https://github.com/Genymobile/scrcpy>.

- Tampilkan layar sebuah perangkat yang terhubung:

```bash
scrcpy
```

- Tampilkan layar perangkat tertentu berdasarkan ID atau alamat IP-nya (temukan menggunakan perintah `adb devices`):

```bash
scrcpy --serial 0123456789abcdef|192.168.0.1:5555
```

- Tampilkan layar dalam mode layar penuh / fullscreen:

```bash
scrcpy --fullscreen
```

- Putarkan tampilan layar perangkat dalam kelipatan 90 derajat (berlawanan arah jarum jam):

```bash
scrcpy --rotation 0|1|2|3
```

- Tunjukkan indikator sentuhan pada perangkat fisik:

```bash
scrcpy --show-touches
```

- Rekam tampilan layar perangkat ke dalam file video tertentu:

```bash
scrcpy --record jalan/menuju/file.mp4
```

- Tentukan direktori yang akan digunakan untuk memindahkan file (non-APK) ke dalam perangkat melalui drag-and-drop:

```bash
scrcpy --push-target jalan/menuju/direktori
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | ipconfig, scrcpy: add Indonesian translation (#6045) * scrcpy: Add "--serial" option Display a mirror of a specific device based on [...] | 2021-05-28T00:47:42 | [0cca0c93c92b](https://github.com/tldr-pages/tldr/commit/0cca0c93c92bd2348d94ccaf2efc1ff580155176)

