---
author: ['lucas schneider', 'Levi Rizki Saputra']
date: 1610111394
title: "git branch"
description: "git branch, Perintah Git utama untuk bekerja dengan cabang (*branch*)."
categories: "common"
---
> Informasi lebih lanjut: <https://git-scm.com/docs/git-branch>.

- Menampilkan daftar cabang lokal. Cabang saat ini ditandai oleh `*`:

```bash
git branch
```

- Menampilkan daftar semua cabang (lokal dan remote):

```bash
git branch -a
```

- Tunjukkan nama cabang saat ini:

```bash
git branch --show-current
```

- Buat cabang baru berdasarkan komit saat ini:

```bash
git branch nama_cabang
```

- Buat cabang baru berdasarkan komit tertentu:

```bash
git branch nama_cabang hash_komit
```

- Ganti nama cabang (harus bukan cabang saat ini untuk melakukannya):

```bash
git branch -m nama_cabang_lama nama_cabang_baru
```

- Hapus cabang lokal (harus bukan cabang saat ini untuk melakukannya):

```bash
git branch -d nama_cabang
```

- Hapus cabang remote:

```bash
git push nama_remote --delete nama_cabang_remote
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | git-branch: add Indonesian translation | 2020-11-01T14:22:27 | [1289d0e06c3d](https://github.com/tldr-pages/tldr/commit/1289d0e06c3db74acb01f2b67bf8fb4ac8bdb463)

