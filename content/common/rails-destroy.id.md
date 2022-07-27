---
author: ['Adinda Praditya']
date: 1633875900
title: "rails destroy, TLDR Pages"
description: "rails destroy, Menghapus Rails _resources_."
categories: "common"
---
> Informasi lebih lanjut: <https://guides.rubyonrails.org/command_line.html#bin-rails-destroy>.

- Menampilkan daftar semua generator yang tersedia untuk menghapus:

```bash
rails destroy
```

- Menghapus model yang bernama Post:

```bash
rails destroy model Post
```

- Menghapus _controller_ yang bernama Post:

```bash
rails destroy controller Posts
```

- Menghapus migrasi yang membuat Posts:

```bash
rails destroy migration CreatePosts
```

- Menghapus _scaffold_ model yang bernama Post:

```bash
rails destroy scaffold Post
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adinda Praditya](mailto:apraditya@gmail.com) | rails*: add Indonesian translation (#6927) | 2021-10-10T16:25:00 | [8dbfe9837368](https://github.com/tldr-pages/tldr/commit/8dbfe98373687158090fdf87218e3029523a218f)

