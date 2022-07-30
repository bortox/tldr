---
author: ['Adinda Praditya']
date: 1633875900
title: "rails routes"
description: "rails routes, Menampilkan daftar _routes_ di aplikasi Rails."
categories: "common"
---
> Informasi lebih lanjut: <https://guides.rubyonrails.org/routing.html>.

- Menampilkan semua _routes_:

```bash
rails routes
```

- Menampilkan semua _routes_ dengan format yang lebih panjang:

```bash
rails routes --expanded
```

- Menampilkan _routes_ yang sebagian cocok dengan nama helper method URL, HTTP verb, atau path URL:

```bash
rails routes -g posts_path|GET|/posts
```

- Menampilkan _routes_ yang memetakan ke controller tertentu:

```bash
rails routes -c posts|Posts|Blogs::PostsController
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adinda Praditya](mailto:apraditya@gmail.com) | rails*: add Indonesian translation (#6927) | 2021-10-10T16:25:00 | [8dbfe9837368](https://github.com/tldr-pages/tldr/commit/8dbfe98373687158090fdf87218e3029523a218f)

