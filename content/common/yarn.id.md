---
author: ['bl-ue', 'Levi Rizki Saputra']
date: 1617493464
title: "yarn"
description: "yarn, Pengelola paket alternatif untuk JavaScript dan Node.js."
categories: "common"
---
> Informasi lebih lanjut: <https://yarnpkg.com>.

- Memasang modul secara global:

```bash
yarn global add nama_modul
```

- Memasang semua dependensi yang dirujuk di berkas `package.json` (`install` adalah opsional):

```bash
yarn install
```

- Memasang modul dan menyimpannya sebagai dependensi ke berkas `package.json` (tambahkan `--dev` untuk menyimpannya sebagai dependensi pengembangan):

```bash
yarn add nama_modul@versi
```

- Mencopot modul dan menghapusnya dari berkas `package.json`:

```bash
yarn remove nama_modul
```

- Membuat berkas `package.json` secara interaktif:

```bash
yarn init
```

- Mengidentifikasi apakah modul merupakan dependensi dan daftar modul lainnya yang bergantung padanya:

```bash
yarn why module_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | yarn: add Indonesian translation | 2020-11-01T14:22:27 | [dbbf6bbafc2d](https://github.com/tldr-pages/tldr/commit/dbbf6bbafc2dccce2c2404619850c437f20c0f4e)

