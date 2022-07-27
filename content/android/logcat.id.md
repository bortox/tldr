---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "logcat, TLDR Pages"
description: "logcat, Menampilkan dan menyimpan log sistem."
categories: "android"
---
> Informasi lebih lanjut: <https://developer.android.com/studio/command-line/logcat>.

- Menampilkan log sistem:

```bash
logcat
```

- Menyimpan log sistem di dalam sebuah file:

```bash
logcat -f path/to/file
```

- Menyaring informasi log berdasarkan sintaks ekspresi reguler (regex) tertentu:

```bash
logcat --regex regular_expression
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

