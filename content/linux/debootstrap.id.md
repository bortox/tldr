---
author: ['Azrael JD']
date: 1642604379
title: "debootstrap"
description: "debootstrap, Membuat sistem Debian dasar."
categories: "linux"
---
> Informasi lebih lanjut: <https://wiki.debian.org/Debootstrap>.

- Membuat sistem Debian stable didalam direktori `debian-root`:

```bash
sudo debootstrap stable jalan/ke/debian-root/ http://deb.debian.org/debian
```

- Membuat sistem minimal termasuk hanya paket yang diperlukan:

```bash
sudo debootstrap --variant=minbase stable jalan/ke/debian-root/
```

- Membuat sistem Ubuntu 20.04 didalam direktori `focal-root` dengan mirror lokal:

```bash
sudo debootstrap focal jalan/ke/focal-root/ file:///jalan/ke/mirror/
```

- Berpindah ke sistem yang telah di bootstrap:

```bash
sudo chroot jalan/ke/root
```

- Memperlihatkan rilis Debian atau Ubuntu yang tersedia:

```bash
ls /usr/share/debootstrap/scripts/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | debootstrap: add Indonesian translation (#7671) | 2022-01-19T15:59:39 | [6f7a1caf6c67](https://github.com/tldr-pages/tldr/commit/6f7a1caf6c67b89cf7dd8565cacb66f88513168b)

