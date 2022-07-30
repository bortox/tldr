---
author: ['Adinda Praditya']
date: 1633875900
title: "rails generate"
description: "rails generate, Membuat Rails templates yang baru ke suatu proyek."
categories: "common"
---
> Informasi lebih lanjut: <https://guides.rubyonrails.org/command_line.html#bin-rails-generate>.

- Menampilkan semua generator yang tersedia:

```bash
rails generate
```

- Membuat model baru bernama Post dengan atribut judul dan uraian:

```bash
rails generate model Post judul:string uraian:text
```

- Mmebuat _controller_ baru bernama Posts dengan actions index, show, new dan create:

```bash
rails generate controller Posts index show new create
```

- Membuat migrasi baru yang menambahkan atribut kategori ke model yang sudah ada bernama Post:

```bash
rails generate migration AddKategoriToPost kategori:string
```

- Membuat _scaffold_ untuk model bernama Post, dengan pendefinisian atribut judul dan uraian:

```bash
rails generate scaffold Post title:string body:text
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adinda Praditya](mailto:apraditya@gmail.com) | rails*: add Indonesian translation (#6927) | 2021-10-10T16:25:00 | [8dbfe9837368](https://github.com/tldr-pages/tldr/commit/8dbfe98373687158090fdf87218e3029523a218f)

