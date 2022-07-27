---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "pm, TLDR Pages"
description: "pm, Menampilkan daftar pemasangan aplikasi di dalam sebuah perangkat Android."
categories: "android"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb#pm>.

- Menampilkan daftar seluruh aplikasi yang terpasang:

```bash
pm list packages
```

- Menampilkan daftar seluruh aplikasi sistem yang terpasang:

```bash
pm list packages -s
```

- Menampilkan daftar seluruh aplikasi pihak ketiga yang terpasang:

```bash
pm list packages -3
```

- Menampilkan daftar aplikasi dengan kata kunci tertentu:

```bash
pm list packages kata_kunci
```

- Menampilkan jalan menuju file APK untuk sebuah aplikasi:

```bash
pm path aplikasi
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

