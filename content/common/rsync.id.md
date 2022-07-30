---
author: ['Adinda Praditya', 'lincc']
date: 1643487459
title: "rsync"
description: "rsync, Transfer file ke atau dari sebuah _remote host_ (bukan di antara 2 _remote host_)."
categories: "common"
---
> Bisa transfer satuan file, maupun beberapa file yang sesuai dengan pola tertentu.

> Informasi lebih lanjut: <https://manned.org/rsync>.

- Transfer file dari lokal ke _remote host_:

```bash
rsync lokasi/ke/file_lokal remote_host:lokasi/ke/remote_directory
```

- Transfer file dari _remote host_ ke lokal:

```bash
rsync remote_host:lokasi/ke/remote_file lokasi/ke/direktori_lokal
```

- Transfer file dalam mode [a]rsip (untuk menyimpan atribut-atribut) dan terkompres (_[z]ipped_) secara _[v]erbose_ dan progresnya dapat dibaca orang (_[h]uman-readable [P]rogress_):

```bash
rsync -azvhP lokasi/ke/file_lokal remote_host:lokasi/ke/remote_directory
```

- Transfer direktori dan semua isiny dari remote ke lokal:

```bash
rsync -r remote_host:lokasi/ke/remote_directory lokasi/ke/direktori_lokal
```

- Transfer isi direktori (namun bukan direktori itu sendiri) dari remote ke lokal:

```bash
rsync -r remote_host:lokasi/ke/remote_directory/ lokasi/ke/direktori_lokal
```

- Transfer direktori secara [r]ecursif, dalam [a]rsip (untuk menyimpan atribut-atribut), menyelesaikan _soft[l]inks_ yang terkandung di sana, dan mengabaikan file-file yang sudah ditransfer kecuali jika file itu lebih baru (_[u]nless newer_):

```bash
rsync -rauL remote_host:lokasi/ke/remote_file lokasi/ke/direktori_lokal
```

- Transfer file melalui SSH dan hapus file-file lokal yang tidak ada di _remote host_:

```bash
rsync -e ssh --delete remote_host:lokasi/ke/remote_file lokasi/ke/file_lokal
```

- Transfer file melalui SSH dengan menggunakan port yang yang berbeda dari bawaan dan tampilkan progres global:

```bash
rsync -e 'ssh -p port' --info=progress2 remote_host:lokasi/ke/remote_file lokasi/ke/file_lokal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Adinda Praditya](mailto:apraditya@gmail.com) | rsync: add Indonesian translation (#6731) | 2021-10-03T23:07:04 | [405362158799](https://github.com/tldr-pages/tldr/commit/40536215879953ff65dc6e57722a3bcdf3a923ba)

