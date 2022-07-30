---
author: ['Nicolas Kosinski', 'Lucas Gabriel Schneider', 'Axel Navarro', 'Irham Dzuhri', 'bl-ue']
date: 1643827401
title: "npm"
description: "npm, Manajer paket JavaScript dan Node.js."
categories: "common"
---
> Mengelola proyek Node.js dan dependensi modulnya.

> Informasi lebih lanjut: <https://www.npmjs.com>.

- Membuat file `package.json` secara interaktif:

```bash
npm init
```

- Unduh semua paket yang terdaftar sebagai dependensi di package.json:

```bash
npm install
```

- Unduh versi tertentu dari sebuah paket dan menambahkan ke daftar dependensi di `package.json`:

```bash
npm install nama_modul@versi
```

- Unduh paket dan menambahkan ke daftar dependensi dev di package.json:

```bash
npm install nama_modul --save-dev
```

- Unduh paket dan instal secara global:

```bash
npm install --global nama_modul
```

- Copot pemasangan paket dan hapus dari daftar dependensi di `package.json`:

```bash
npm uninstall nama_modul
```

- Mencetak pohon dependensi yang diinstal secara lokal:

```bash
npm list
```

- Buat daftar modul tingkat atas yang diinstal secara global:

```bash
npm list --global --depth=0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | npm: use long argument --global (#5880) | 2021-05-04T09:26:22 | [1fe05c4e59dd](https://github.com/tldr-pages/tldr/commit/1fe05c4e59ddbb8aebbd121f692cd3b743087724)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Irham Dzuhri](mailto:irhamdz@gmail.com) | curl, docker, git, git-add, git-commit, git-status, npm: add Indonesian translation (#4602) | 2020-10-12T23:51:19 | [9f52c5371c1b](https://github.com/tldr-pages/tldr/commit/9f52c5371c1baeffc86b9dd2f651ebedb493700b)

