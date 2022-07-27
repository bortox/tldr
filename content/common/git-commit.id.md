---
author: ['Irham Dzuhri', 'bl-ue', 'Tan A']
date: 1616156811
title: "git commit, TLDR Pages"
description: "git commit, Komit file ke dalam sebuah repositori."
categories: "common"
---
> Informasi lebih lanjut: <https://git-scm.com/docs/git-commit>.

- Komit file bertahap ke repositori dengan sebuah pesan:

```bash
git commit -m "pesan"
```

- Otomatis merubah semua file yang dimodifikasi menjadi ke status stage dan menambahkan sebuah pesan:

```bash
git commit -a -m "pesan"
```

- Ganti komit terakhir dengan perubahan yang ada di status stage saat ini:

```bash
git commit --amend
```

- Komit file tertentu (yang sudah di status stage):

```bash
git commit alamat/ke/file/saya1 alamat/ke/file/saya2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Irham Dzuhri](mailto:irhamdz@gmail.com) | curl, docker, git, git-add, git-commit, git-status, npm: add Indonesian translation (#4602) | 2020-10-12T23:51:19 | [9f52c5371c1b](https://github.com/tldr-pages/tldr/commit/9f52c5371c1baeffc86b9dd2f651ebedb493700b)

