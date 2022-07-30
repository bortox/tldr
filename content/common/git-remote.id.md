---
author: ['Levi Rizki Saputra']
date: 1604236947
title: "git remote"
description: "git remote, Mengelola kumpulan repositori yang dilacak/diikuti ('remotes')."
categories: "common"
---
> Informasi lebih lanjut: <https://git-scm.com/docs/git-remote>.

- Menampilkan daftar remote, namanya dan URL:

```bash
git remote -v
```

- Menampilkan informasi tentang remote:

```bash
git remote show nama_remote
```

- Menambahkan remote:

```bash
git remote add nama_remote url_remote
```

- Mengubah URL dari remote (gunakan `--add` untuk tetap menyimpan URL lama):

```bash
git remote set-url nama_remote url_baru
```

- Menghapus remote:

```bash
git remote remove nama_remote
```

- Mengubah nama remote:

```bash
git remote rename nama_lama nama_baru
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | git-remote: add Indonesian translation | 2020-11-01T14:22:27 | [30aeec9d008b](https://github.com/tldr-pages/tldr/commit/30aeec9d008b10630092bd7a447d8c68f3ff7a6c)

