---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "settings, TLDR Pages"
description: "settings, Menampilkan informasi terhadap pengaturan sistem operasi Android."
categories: "android"
---
> Informasi lebih lanjut: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Menampilkan daftar pengaturan di dalam namespace `global`:

```bash
settings list global
```

- Menampilkan nilai dari pengaturan tertentu:

```bash
settings get global airplane_mode_on
```

- Menyetel nilai pengaturan tertentu:

```bash
settings put system screen_brightness 42
```

- Menghapus nilai pengaturan tertentu:

```bash
settings delete secure screensaver_enabled
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)

