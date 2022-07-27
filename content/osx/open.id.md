---
author: ['Reinhart Previano Koentjoro']
date: 1657535896
title: "open, TLDR Pages"
description: "open, Membuka file, direktori, dan aplikasi."
categories: "osx"
---
> Informasi lebih lanjut: <https://ss64.com/osx/open.html>.

- Membuka sebuah file di dalam aplikasi default:

```bash
open file.ext
```

- Membuka aplikasi macOS tertentu:

```bash
open -a "Aplikasi"
```

- Membuka sebuah aplikasi macOS berdasarkan ID pengenal (bundle identifier) tertentu (gunakan `osascript` untuk mencari ID pengenal aplikasi secara mudah dan cepat):

```bash
open -b com.domain.aplikasi
```

- Buka direktori saat ini di dalam aplikasi Finder:

```bash
open .
```

- Lihat sebuah file di dalam aplikasi Finder:

```bash
open -R jalan/menuju/file
```

- Buka semua file dengan ekstensi tertentu di dalam aplikasi default pada direktori saat ini:

```bash
open *.ext
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | open, osascript: add Indonesian translation (#8178) | 2022-07-11T12:38:16 | [d57f612d99e8](https://github.com/tldr-pages/tldr/commit/d57f612d99e8e8a93ae48fd151e0373ea24c83f6)

