---
author: ['Ilya Pantsyr']
date: 1650144840
title: "git merge"
description: "git merge, Злиття гілок разом."
categories: "common"
---
> Більше інформації: <https://git-scm.com/docs/git-merge>.

- Злиття гілки з поточною гілкою:

```bash
git merge назва_гілки
```

- Редагує повідомлення при злитті гілок:

```bash
git merge -e назва_гілки
```

- Зливає гілки і створює комміт злиття:

```bash
git merge --no-ff назва_гілки
```

- Перериває злиття у випадку конфлікту:

```bash
git merge --abort
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | git-merge: add Ukrainian translation (#8028) | 2022-04-16T23:34:00 | [fe3a6efb95c4](https://github.com/tldr-pages/tldr/commit/fe3a6efb95c477b856464e8426195048aaf4aa81)

