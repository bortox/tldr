---
author: ['Nelson Figueroa']
date: 1617880227
title: "rails generate"
description: "rails generate, Generate new Rails templates in an existing project."
categories: "common"
---
> More information: <https://guides.rubyonrails.org/command_line.html#bin-rails-generate>.

- List all available generators:

```bash
rails generate
```

- Generate a new model named Post with attributes title and body:

```bash
rails generate model Post title:string body:text
```

- Generate a new controller named Posts with actions index, show, new and create:

```bash
rails generate controller Posts index show new create
```

- Generate a new migration that adds a category attribute to an existing model called Post:

```bash
rails generate migration AddCategoryToPost category:string
```

- Generate a scaffold for a model named Post, predefining the attributes title and body:

```bash
rails generate scaffold Post title:string body:text
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | rails-generate: fix more information link (#5706) | 2021-04-08T13:10:27 | [4ff745fdadbf](https://github.com/tldr-pages/tldr/commit/4ff745fdadbf22f5cb63d28be02a2deb7645feed)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | rails-generate: add migration (#3975) | 2020-04-15T18:29:07 | [ec911e0308e6](https://github.com/tldr-pages/tldr/commit/ec911e0308e6d2835989be8c1b9f11f554bb8511)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | rails-generate: add page (#2794) | 2019-02-21T22:10:14 | [45b9aeaf9443](https://github.com/tldr-pages/tldr/commit/45b9aeaf944384559a57c3302ac82afc7a51bada)

