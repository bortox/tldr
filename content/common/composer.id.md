---
author: ['Zein Haddad']
date: 1644918669
title: "composer"
description: "composer, Manajer paket untuk proyek PHP."
categories: "common"
---
> Informasi lebih lanjut: <https://getcomposer.org/>.

- Membuat file `composer.json` secara interaktif:

```bash
composer init
```

- Menambahkan paket sebagai dependensi untuk proyek ini, menambahkan ke `composer.json`:

```bash
composer require user/nama_paket
```

- Menginstal semua dependensi dalam `composer.json` proyek ini dan membuat `composer.lock`:

```bash
composer install
```

- Menghapus sebuah paket dari proyek ini, menghapus paket tersebut sebagai ketergantungan dari `composer.json`:

```bash
composer remove user/nama_paket
```

- Memperbarui semua dependensi dalam `composer.json` proyek ini dan memperbarui versi di file `composer.lock`:

```bash
composer update
```

- Memperbarui `composer.lock` setelah mengubah `composer.json` secara manual:

```bash
composer update --lock
```

- Memcari tahu mengapa sebuah dependensi tidak dapat diinstal:

```bash
composer why-not user/nama_paket
```

- Memperbarui composer ke versi terbaru:

```bash
composer self-update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zein Haddad](mailto:zeinhaddad02@gmail.com) | composer, subl: add Indonesian translation (#7780) | 2022-02-15T10:51:09 | [233b10de4fed](https://github.com/tldr-pages/tldr/commit/233b10de4fedaafeb78c710747f3944d70b8a672)

