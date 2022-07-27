---
author: ['Zein Haddad']
date: 1644839080
title: "dnf, TLDR Pages"
description: "dnf, Manajer paket untuk distribusi Linux RHEL, Fedora, dan CentOS (pengganti yum)."
categories: "linux"
---
> Informasi lebih lanjut: <https://dnf.readthedocs.io>.

- Memperbarui seluruh paket yang terpasang ke versi terbaru:

```bash
sudo dnf upgrade
```

- Mencari paket yang tersedia dengan kata kunci tertentu:

```bash
dnf search kata_kunci
```

- Memperlihatkan informasi tentang suatu paket:

```bash
dnf info nama_paket
```

- Menginstal sebuah paket:

```bash
sudo dnf install nama_paket
```

- Menginstal sebuah paket dan jawab ya untuk semua pertanyaan:

```bash
sudo dnf -y install nama_paket
```

- Menghapus sebuah paket:

```bash
sudo dnf remove nama_paket
```

- Memperlihatkan daftar semua paket yang telah terpasang:

```bash
dnf list --installed
```

- Temukan paket mana yang menyediakan file tertentu:

```bash
dnf provides file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zein Haddad](mailto:zeinhaddad02@gmail.com) | dnf, youtube-dl: add Indonesian translation (#7766) | 2022-02-14T12:44:40 | [2db31619792a](https://github.com/tldr-pages/tldr/commit/2db31619792ac45f8bd79a368b5e10dc51690702)

