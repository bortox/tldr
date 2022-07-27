---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "am, TLDR Pages"
description: "am, Manajer aktivitas untuk Android."
categories: "android"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/adb#am>.

- Memulai aktivitas tertentu:

```bash
am start -n com.android.settings/.Settings
```

- Memulai aktivitas dengan data yang ditentukan:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Memulai aktivitas dengan aksi dan kategori tertentu:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Mengubah sebuah Intent menjadi tautan URI:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

