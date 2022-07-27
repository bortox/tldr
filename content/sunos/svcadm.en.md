---
author: ['Ruben Vereecken', 'Srinivasan R', 'rprieto', 'marchersimon']
date: 1617188954
title: "svcadm, TLDR Pages"
description: "svcadm, Manipulate service instances."
categories: "sunos"
---
> More information: <https://www.unix.com/man-page/linux/1m/svcadm>.

- Enable a service in the service database:

```bash
svcadm enable service_name
```

- Disable service:

```bash
svcadm disable service_name
```

- Restart a running service:

```bash
svcadm restart service_name
```

- Command service to re-read configuration files:

```bash
svcadm refresh service_name
```

- Clear a service from maintenance state and command it to start:

```bash
svcadm clear service_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

