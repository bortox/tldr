---
author: ['Levi Rizki Saputra']
date: 1603629602
title: "adb shell"
description: "adb shell, Android Debug Bridge Shell: Menjalankan perintah shell jarak jauh pada emulator Android atau perangkat Android terhubung."
categories: "common"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb>.

- Memulai shell interaktif jarak jauh di emulator/perangkat:

```bash
adb shell
```

- Mendapatkan semua properti dari emulator/perangkat:

```bash
adb shell getprop
```

- Mengembalikan semua izin runtime ke default:

```bash
adb shell pm reset-permissions
```

- Mencabut izin berbahaya dari sebuah aplikasi:

```bash
adb shell pm revoke paket izin
```

- Memicu sebuah peristiwa penting:

```bash
adb shell input keyevent keycode
```

- Mengosongkan data aplikasi pada emulator/perangkat:

```bash
adb shell pm clear paket
```

- Memulai aktivitas pada emulator/perangkat:

```bash
adb shell am start -n paket/aktivitas
```

- Memulai aktivitas beranda pada emulator/perangkat:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

