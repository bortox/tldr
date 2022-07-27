---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Joel Huang', 'Sadeed', 'Dmitry']
date: 1634674843
title: "unrar, TLDR Pages"
description: "unrar, Extract RAR archives."
categories: "common"
---
> More information: <https://manned.org/unrar>.

- Extract files with original directory structure:

```bash
unrar x compressed.rar
```

- Extract files to a specified path with the original directory structure:

```bash
unrar x compressed.rar path/to/extract
```

- Extract files into current directory, losing directory structure in the archive:

```bash
unrar e compressed.rar
```

- Test integrity of each file inside the archive file:

```bash
unrar t compressed.rar
```

- List files inside the archive file without decompressing it:

```bash
unrar l compressed.rar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | ufraw-batch, ulimit, umask, umount, unalias, unar, unclutter, unrar, unzip: add link (#7092) | 2021-10-19T22:20:43 | [02441ef2ba43](https://github.com/tldr-pages/tldr/commit/02441ef2ba43268b294d2148ff1c7aa439a2d9ec)
[Dmitry](mailto:d9k@ya.ru) | unrar: extract to another directory example (#4088) | 2020-06-21T10:02:41 | [533c40946509](https://github.com/tldr-pages/tldr/commit/533c40946509651c6c5c043a7b7a97dab137e37f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | unrar: reorder examples extracting with original directory structure is arguably a more common use case than extracting the files in a [...] | 2016-01-05T18:31:30 | [d7ab35d47321](https://github.com/tldr-pages/tldr/commit/d7ab35d47321a5d25e5962d5cba2993c9eeef0f9)
[Joel Huang](mailto:joelhy@gmail.com) | unrar: add page | 2016-01-05T12:52:36 | [45e74285a3d8](https://github.com/tldr-pages/tldr/commit/45e74285a3d82bd114af4659dc8782501b613c7b)

