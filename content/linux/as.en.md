---
author: ['Agniva De Sarker', 'Stig124', 'Lucas Gabriel Schneider']
date: 1625841955
title: "as, TLDR Pages"
description: "as, Portable GNU assembler."
categories: "linux"
---
> Primarily intended to assemble output from `gcc` to be used by `ld`.

> More information: <https://manned.org/as>.

- Assemble a file, writing the output to `a.out`:

```bash
as file.s
```

- Assemble the output to a given file:

```bash
as file.s -o out.o
```

- Generate output faster by skipping whitespace and comment preprocessing. (Should only be used for trusted compilers):

```bash
as -f file.s
```

- Include a given path to the list of directories to search for files specified in `.include` directives:

```bash
as -I path/to/directory file.s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | as: add page (#2128) | 2018-06-13T18:48:28 | [2ddd4f552c3b](https://github.com/tldr-pages/tldr/commit/2ddd4f552c3b14acaadeb4157ca59b136005f642)

