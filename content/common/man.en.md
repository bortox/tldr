---
author: ['Waldir Pimenta', 'Patrice Denis', 'rprieto', 'Ruben Vereecken', 'cjc7373', 'Noy', 'fetlang', 'Rui Alves', 'Guido Lena Cota']
date: 1657008405
title: "man, TLDR Pages"
description: "man, Format and display manual pages."
categories: "common"
---
> More information: <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Display the man page for a command:

```bash
man command
```

- Display the man page for a command from section 7:

```bash
man 7 command
```

- List all available sections for a command:

```bash
man -f command
```

- Display the path searched for manpages:

```bash
man --path
```

- Display the location of a manpage rather than the manpage itself:

```bash
man -w command
```

- Display the man page using a specific locale:

```bash
man command --locale=locale
```

- Search for manpages containing a search string:

```bash
man -k "search_string"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cjc7373](mailto:niuchangcun@gmail.com) | man: add -f example (#8180) | 2022-07-05T10:06:45 | [6588dd75078a](https://github.com/tldr-pages/tldr/commit/6588dd75078a1a6954403afd0aa50e4073922867)
[Noy](mailto:nbaltunian@gmail.com) | man: correct syntax (#6505) | 2021-09-13T14:42:11 | [efeee14594da](https://github.com/tldr-pages/tldr/commit/efeee14594dab9cc5dd082f03a53dbfa83298fb0)
[Patrice Denis](mailto:patrice.denis@gmail.com) | man: add more info link and --locale example (#5504) | 2021-03-25T22:54:01 | [b431ae33f75d](https://github.com/tldr-pages/tldr/commit/b431ae33f75dbfc3d554f9e611b4f1301ce12885)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Rui Alves](mailto:up201606746@fe.up.pt) | man: improve grammar | 2019-10-13T05:29:44 | [aa36609be54d](https://github.com/tldr-pages/tldr/commit/aa36609be54d2cda894cd2d915e064bc7d371f1a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | man: clarify search example | 2019-07-24T05:28:57 | [48e6e6554a0f](https://github.com/tldr-pages/tldr/commit/48e6e6554a0f863c2a4f5be86d818d310252b1bf)
[fetlang](mailto:36645009+fetlang@users.noreply.github.com) | man: add example for choosing page section (#2102) | 2018-05-08T14:59:38 | [72b510577640](https://github.com/tldr-pages/tldr/commit/72b510577640097d47824fbea7e06f22d8999d07)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

