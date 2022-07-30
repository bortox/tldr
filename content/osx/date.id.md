---
author: ['Raynaldo Sutisna']
date: 1635078903
title: "date"
description: "date, Mengatur atau menampilkan tanggal sistem."
categories: "osx"
---
> Informasi lebih lanjut: <https://ss64.com/osx/date.html>.

- Menampilkan tanggal saat ini menggunakan format _locale_:

```bash
date +"%c"
```

- Menampilkan tanggal saat ini dalam format UTC and ISO 8601:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- Menampilkan tanggal saat ini sebagai _Unix timestamp_ (detik sejak jaman Unix):

```bash
date +%s
```

- Menampilkan tanggal tertentu (diwakili sebagai _Unix timestamp_) menggunakan format bawaan:

```bash
date -r 1473305798
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raynaldo Sutisna](mailto:raaynaldo@gmail.com) | date: add Indonesian translation (#7121) | 2021-10-24T14:35:03 | [8f3b2e9f45bb](https://github.com/tldr-pages/tldr/commit/8f3b2e9f45bbbe80eceb836b494337fd6c31c7a0)

