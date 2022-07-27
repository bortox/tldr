---
author: ['Azrael JD', 'Axel Navarro']
date: 1641649180
title: "dpkg, TLDR Pages"
description: "dpkg, Manajer paket Debian."
categories: "linux"
---
> Beberapa subperintah seperti `dpkg deb` memiliki dokumentasi penggunaannya sendiri.

> Informasi lebih lanjut: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Memasang paket dari sebuah file DEB:

```bash
dpkg -i jalan/menuju/file.deb
```

- Menghapus pemasangan sebuah paket:

```bash
dpkg -r nama_paket
```

- Memperlihatkan daftar paket terinstal:

```bash
dpkg -l pola
```

- Memperlihatkan isi sebuah paket:

```bash
dpkg -L nama_paket
```

- Memperlihatkan isi sebuah paket lokal:

```bash
dpkg -c jalan/menuju/file.deb
```

- Mencari tahu paket yang memiliki sebuah file:

```bash
dpkg -S nama_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | apt, dpkg: add Indonesian translation (#7614) | 2022-01-06T14:03:52 | [8013703e70f4](https://github.com/tldr-pages/tldr/commit/8013703e70f40c959856002ead5b785e8b70007c)

