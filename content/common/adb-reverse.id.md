---
author: ['Levi Rizki Saputra']
date: 1603629602
title: "adb reverse, TLDR Pages"
description: "adb reverse, Android Debug Bridge Reverse: membalik koneksi socket dari emulator Android atau perangkat Android terhubung."
categories: "common"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb>.

- Daftar semua koneksi socket terbalik dari emulator dan perangkat:

```bash
adb reverse --list
```

- Membalik port TCP dari emulator/perangkat ke localhost:

```bash
adb reverse tcp:port_jarak_jauh tcp:port_lokal
```

- Melepas koneksi socket terbalik dari emulator/perangkat:

```bash
adb reverse --remove tcp:port_jarak_jauh
```

- Melepas semua koneksi socket terbalik dari semua emulator dan perangkat:

```bash
adb reverse --remove-all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

