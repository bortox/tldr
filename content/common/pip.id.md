---
author: ['Noah', 'Levi Rizki Saputra', 'marchersimon']
date: 1636291516
title: "pip, TLDR Pages"
description: "pip, Pengelola paket Python."
categories: "common"
---
> Kami mempunyai dokumentasi terpisah untuk menggunakan subperintah seperti `pip install`.

> Informasi lebih lanjut: <https://pip.pypa.io>.

- Memasang paket:

```bash
pip install nama_paket
```

- Memasang versi paket tertentu:

```bash
pip install nama_paket==versi_paket
```

- Memasang paket untuk hanya digunakan oleh pengguna saat ini:

```bash
pip install --user nama_paket
```

- Meningkatakan paket ke versi terbaru:

```bash
pip install --upgrade nama_paket
```

- Mencopot pemasangan paket:

```bash
pip uninstall nama_paket
```

- Menyimpan daftar paket terpasang ke berkas:

```bash
pip freeze > requirements.txt
```

- Memasang paket dari berkas:

```bash
pip install --requirement requirements.txt
```

- Menampilkan informasi paket terpasang:

```bash
pip show nama_paket
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Noah](mailto:nbaltunian@gmail.com) | pip: synchronize long options, formatting and add --user example (#6605) | 2021-11-07T14:25:16 | [4042138a51c8](https://github.com/tldr-pages/tldr/commit/4042138a51c845a4fff7744f4c6ffc76cdc14e12)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)

