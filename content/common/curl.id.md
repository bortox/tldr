---
author: ['Irham Dzuhri', 'bl-ue', 'Nicolas Kosinski']
date: 1620121027
title: "curl"
description: "curl, Mentransfer data dari atau ke server."
categories: "common"
---
> Mendukung sebagian besar protokol, termasuk HTTP, FTP, dan POP3.

> Informasi lebih lanjut: <https://curl.se>.

- Unduh konten URL ke file:

```bash
curl http://contoh.com --output namafile
```

- Unduh file, simpan hasilnya dengan nama file yang ditentukan oleh URL:

```bash
curl --remote-name http://contoh.com/namafile
```

- Unduh file, mengikuti pengalihan lokasi, dan secara otomatis melanjutkan transfer file sebelumnya:

```bash
curl --remote-name --location --continue-at - http://contoh.com/filename
```

- Mengirim data form yang telah di encode (permintaan POST atau tipe data `application/x-www-form-urlencoded`). Gunakan `--data @file_name` atau `--data @'-'` untuk membaca dari STDIN:

```bash
curl --data 'name=bob' http://contoh.com/form
```

- Mengirim sebuah permintaan dengan header tambahan, menggunakan metode HTTP kustom:

```bash
curl --header 'X-My-Header: 123' --request PUT http://contoh.com
```

- Mengirim data dalam format JSON, Menentukan jenis konten yang sesuai header:

```bash
curl --data '{"name":"bob"}' --header 'Content-Type: application/json' http://contoh.com/users/1234
```

- Memberikan nama pengguna dan kata sandi untuk otentikasi server:

```bash
curl --user myusername:mypassword http://contoh.com
```

- Memberikan sertifikat klien dan kunci untuk sumber daya, melewati validasi sertifikat:

```bash
curl --cert client.pem --key key.pem --insecure https://contoh.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Irham Dzuhri](mailto:irhamdz@gmail.com) | curl, docker, git, git-add, git-commit, git-status, npm: add Indonesian translation (#4602) | 2020-10-12T23:51:19 | [9f52c5371c1b](https://github.com/tldr-pages/tldr/commit/9f52c5371c1baeffc86b9dd2f651ebedb493700b)

