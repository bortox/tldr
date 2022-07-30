---
author: ['Reinhart Previano Koentjoro']
date: 1657535896
title: "osascript"
description: "osascript, Jalankan AppleScript atau JavaScript for Automation (JXA) dari command-line."
categories: "osx"
---
> Informasi lebih lanjut: <https://ss64.com/osx/osascript.html>.

- Menjalankan sebuah perintah AppleScript:

```bash
osascript -e "say 'Halo dunia'"
```

- Menjalankan beberapa perintah AppleScript:

```bash
osascript -e "say 'Halo'" -e "say 'dunia'"
```

- Mengeksekusi perintah dari file AppleScript yang telah terkompilasi (`*.scpt`), terbundel (`*.scptd`), atau secara plaintext (`*.applescript`):

```bash
osascript jalan/menuju/apple.scpt
```

- Mendapatkan ID pengenal (bundle identifier) dari sebuah aplikasi (dapat digunakan untuk perintah `open -b`):

```bash
osascript -e 'id of app "Aplikasi"'
```

- Menjalankan sebuah perintah JavaScript:

```bash
osascript -l JavaScript -e "console.log('Halo dunia');"
```

- Mengeksekusi perintah dari file JavaScript:

```bash
osascript -l JavaScript jalan/menuju/javascript.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | open, osascript: add Indonesian translation (#8178) | 2022-07-11T12:38:16 | [d57f612d99e8](https://github.com/tldr-pages/tldr/commit/d57f612d99e8e8a93ae48fd151e0373ea24c83f6)

