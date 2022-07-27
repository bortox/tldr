---
author: ['Levi Rizki Saputra']
date: 1604236947
title: "git clone, TLDR Pages"
description: "git clone, Mengkloning repositori yang ada."
categories: "common"
---
> Informasi lebih lanjut: <https://git-scm.com/docs/git-clone>.

- Mengkloning repositori yang ada:

```bash
git clone lokasi_repositori_remote
```

- Mengkloning reposiori yang ada dan submodulenya:

```bash
git clone --recursive lokasi_repositori_remote
```

- Mengkloning repositori lokal:

```bash
git clone -l alamat/ke/repository/lokal
```

- Mengkloning dengan senyap:

```bash
git clone -q lokasi_repositori_remote
```

- Mengkloning repositori yang sudah ada dengan hanya mengambil 10 komit paling baru pada branch default (berguna untuk menghemat waktu):

```bash
git clone --depth 10 lokasi_repositori_remote
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | git-clone: add Indonesian translation | 2020-11-01T14:22:27 | [d80109789100](https://github.com/tldr-pages/tldr/commit/d80109789100bbc6de292399856f93bd8d3f4a59)

