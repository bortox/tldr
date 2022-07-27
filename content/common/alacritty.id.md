---
author: ['Lucas Gabriel Schneider', 'bl-ue', 'Levi Rizki Saputra']
date: 1621541621
title: "alacritty, TLDR Pages"
description: "alacritty, Lintas platform, terakselerasi GPU terminal emulator."
categories: "common"
---
> Informasi lebih lanjut: <https://github.com/alacritty/alacritty>.

- Membuka jendela Alacritty baru:

```bash
alacritty
```

- Menjalankan Alacritty pada direktori tertentu:

```bash
alacritty --working-directory alamat/ke/direktori
```

- Menjalankan perintah di jendela Alacritty baru:

```bash
alacritty -e perintah
```

- Menentukan berkas konfigurasi alternatif (nilai default `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

```bash
alacritty --config-file alamat/ke/konfigurasi.yml
```

- Menjalankan dengan mengaktifkan pemuatan ulang konfigurasi secara langsung/otomatis (dapat juga diaktifkan secara default di `alacritty.yml`):

```bash
alacritty --live-config-reload --config-file alamat/ke/konfigurasi.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | aapt, adb*, alacritty, apktool, asar, node, nvim: add Indonesian translation (#4829) | 2020-10-25T13:40:02 | [2e2243e36332](https://github.com/tldr-pages/tldr/commit/2e2243e36332cda1495639d8868ee75a128a6633)

