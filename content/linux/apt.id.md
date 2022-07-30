---
author: ['Azrael JD']
date: 1641474232
title: "apt"
description: "apt, Manajer paket untuk distribusi Linux berbasis Debian."
categories: "linux"
---
> Pengganti `apt-get` yang direkomendasikan ketika digunakan secara interaktif di Ubuntu versi 16.04 atau yang lebih baru.

> Informasi lebih lanjut: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Memperbarui daftar paket yang tersedia dan versinya (direkomendasikan untuk menggunakan perintah ini sebelum perintah `apt` lainnya.):

```bash
sudo apt update
```

- Mencari paket yang tersedia dengan nama atau deskripsi tertentu:

```bash
apt search nama_atau_deskripsi_paket
```

- Memperlihatkan informasi tentang suatu paket:

```bash
apt show nama_paket
```

- Menginstal sebuah paket, atau memperbarui paket ke versi terbaru:

```bash
sudo apt install nama_paket
```

- Menghapus sebuah paket (gunakan `sudo apt purge` untuk menghapus paket beserta file konfigurasinya):

```bash
sudo apt remove nama_paket
```

- Memperbarui seluruh paket yang terpasang ke versi terbaru:

```bash
sudo apt upgrade
```

- Memperlihatkan daftar semua paket yang tersedia di dalam repositori:

```bash
apt list
```

- Memperlihatkan daftar paket yang telah terpasang:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | apt, dpkg: add Indonesian translation (#7614) | 2022-01-06T14:03:52 | [8013703e70f4](https://github.com/tldr-pages/tldr/commit/8013703e70f40c959856002ead5b785e8b70007c)

