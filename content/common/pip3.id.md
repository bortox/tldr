---
author: ['Seth Falco', 'Levi Rizki Saputra']
date: 1623981137
title: "pip3, TLDR Pages"
description: "pip3, Pengelola paket Python."
categories: "common"
---
> Informasi lebih lanjut: <https://pip.pypa.io>.

- Menemukan paket tersedia:

```bash
pip3 search nama_paket
```

- Memasang paket:

```bash
pip3 install nama_paket
```

- Memasang versi paket tertentu:

```bash
pip3 install nama_paket==versi_paket
```

- Meningkatkan paket ke versi terbaru:

```bash
pip3 install --upgrade nama_paket
```

- Mencopot pemasangan paket:

```bash
pip3 uninstall nama_paket
```

- Menyimpan daftar paket terpasang ke berkas:

```bash
pip3 freeze > requirements.txt
```

- Memasang paket dari berkas:

```bash
pip3 install --requirement requirements.txt
```

- Menampilkan informasi paket terinstal:

```bash
pip3 show nama_paket
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | pip3: fix argument spelling (#6140) | 2021-06-18T03:52:17 | [f50ae7e90575](https://github.com/tldr-pages/tldr/commit/f50ae7e90575c96caf4175bf38497df2edce06d3)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)

