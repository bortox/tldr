---
author: ['Reinhart Previano Koentjoro']
date: 1622155662
title: "ipconfig"
description: "ipconfig, Menampilkan dan mengatur konfigurasi jaringan dalam sistem operasi Windows."
categories: "windows"
---
> Informasi lebih lanjut: <https://docs.microsoft.com/windows-server/administration/windows-commands/ipconfig>.

- Menunjukkan daftar adaptor jaringan:

```bash
ipconfig
```

- Menunjukkan daftar adaptor jaringan secara lengkap:

```bash
ipconfig /all
```

- Memperbarui alamat IP sebuah adaptor jaringan:

```bash
ipconfig /renew adaptor
```

- Mengosongkan alamat-alamat IP yang disetel dalam sebuah adaptor jaringan:

```bash
ipconfig /release adaptor
```

- Mengosongkan cache DNS:

```bash
ipconfig /flushdns
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | ipconfig, scrcpy: add Indonesian translation (#6045) * scrcpy: Add "--serial" option Display a mirror of a specific device based on [...] | 2021-05-28T00:47:42 | [0cca0c93c92b](https://github.com/tldr-pages/tldr/commit/0cca0c93c92bd2348d94ccaf2efc1ff580155176)

