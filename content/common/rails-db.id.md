---
author: ['Adinda Praditya']
date: 1633875900
title: "rails db"
description: "rails db, Beragam subperintah yang berkaitan dengan database untuk Rauby on Rails."
categories: "common"
---
> Informasi lebih lanjut: <https://guides.rubyonrails.org/command_line.html>.

- Membuat database, memuat skema dan menginisiasinya dengan data awal:

```bash
rails db:setup
```

- Mengakses konsol database:

```bash
rails db
```

- Membuat database yang didefinisikan di environment saat ini:

```bash
rails db:create
```

- Menghapus database yang didefinisikan di environment saat ini:

```bash
rails db:drop
```

- Menjalankan migrasi yang belum:

```bash
rails db:migrate
```

- Menampilkan status dari masing-masing file migrasi:

```bash
rails db:migrate:status
```

- Rollback ke migrasi sebelumnya:

```bash
rails db:rollback
```

- Mengisi database dengan data yang didefinisikan di `db/seeds.rb`:

```bash
rails db:seed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adinda Praditya](mailto:apraditya@gmail.com) | rails*: add Indonesian translation (#6927) | 2021-10-10T16:25:00 | [8dbfe9837368](https://github.com/tldr-pages/tldr/commit/8dbfe98373687158090fdf87218e3029523a218f)

