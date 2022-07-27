---
author: ['Reinhart Previano Koentjoro']
date: 1639319694
title: "nvm, TLDR Pages"
description: "nvm, Memasang, melepas, atau mengganti versi Node.js yang dipakai."
categories: "common"
---
> Mendukung nomor versi seperti "12.8" or "v16.13.1", dan label versi seperti "stable", "system", dsb.

> Informasi lebih lanjut: <https://github.com/creationix/nvm>.

- Memasang versi Node.js yang ditentukan:

```bash
nvm install versi_node_js
```

- Menggunakan versi Node.js tertentu untuk sesi saat ini:

```bash
nvm use versi_node_js
```

- Menyetel versi Node.js secara default:

```bash
nvm alias default versi_node_js
```

- Menunjukkan daftar versi Node.js yang tersedia dan versi Node.js yang disetel sebagai default:

```bash
nvm list
```

- Menghapus sebuah versi Node.js yang terpasang melalui `nvm`:

```bash
nvm uninstall versi_node_js
```

- Menjalankan interpreter (REPL) Node.js dengan versi tertentu:

```bash
nvm run versi_node_js --version
```

- Menjalankan sebuah file atau aplikasi JavaScript di dalam Node.js versi tertentu:

```bash
nvm exec versi_node_js node app.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | nvm: update versions in command description (#7518) | 2021-12-12T15:34:54 | [a0bb234f064f](https://github.com/tldr-pages/tldr/commit/a0bb234f064feaeb8e225fb28cbb319c481e3dde)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | nvm: add Indonesian translation (#6068) | 2021-06-08T13:33:21 | [f30dfe524c22](https://github.com/tldr-pages/tldr/commit/f30dfe524c22d670aee6ea16b9608621dacd0ccf)

