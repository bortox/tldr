---
author: ['Ruben Vereecken', 'rprieto', 'marchersimon']
date: 1617188954
title: "svcs, TLDR Pages"
description: "svcs, List information about running services."
categories: "sunos"
---
> More information: <https://www.unix.com/man-page/linux/1/svcs>.

- List all running services:

```bash
svcs
```

- List services that are not running:

```bash
svcs -vx
```

- List information about a service:

```bash
svcs apache
```

- Show location of service log file:

```bash
svcs -L apache
```

- Display end of a service log file:

```bash
tail $(svcs -L apache)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

