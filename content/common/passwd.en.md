---
author: ['Amine Hajyoussef', 'lord63', 'rprieto', 'Ruben Vereecken', 'Scattered Faith', 'Ivan Aracki', 'Joshua Shanks', 'Guido Lena Cota', "Walter O'Keefe"]
date: 1633563243
title: "passwd, TLDR Pages"
description: "passwd, Passwd is a tool used to change a user's password."
categories: "common"
---
> More information: <https://manned.org/passwd>.

- Change the password of the current user interactively:

```bash
passwd
```

- Change the password of a specific user:

```bash
passwd username
```

- Get the current status of the user:

```bash
passwd -S
```

- Make the password of the account blank (it will set the named account passwordless):

```bash
passwd -d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | nslookup, objdump, pactl, passwd, patch: add link (#6828) | 2021-10-07T01:34:03 | [d91120d92e31](https://github.com/tldr-pages/tldr/commit/d91120d92e31e12fa2bd5723fb386d9fe05438bf)
[Scattered Faith](mailto:32654272+Scattered-Faith@users.noreply.github.com) | passwd: remove invalid example (#5691) passwd doesn't accept changing a password via specifying the password after the username in the [...] | 2021-04-27T19:19:59 | [8707d0592581](https://github.com/tldr-pages/tldr/commit/8707d059258191e003f646ce5c80b4e54c9da3d2)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | passwd: add base command (#3869) Co-authored-by: Marco Bonelli <marco@mebeim.net> | 2020-02-24T23:41:14 | [eec1815b50fa](https://github.com/tldr-pages/tldr/commit/eec1815b50faf832795759ac6d0a85f98d7e5c26)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Walter O'Keefe](mailto:wtok@users.noreply.github.com) | passwd: Fix typo (#894) | 2016-05-18T10:32:06 | [084986a76ba8](https://github.com/tldr-pages/tldr/commit/084986a76ba8998c203d146f9c5ec9c7f314ec89)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | consistent markup | 2015-12-31T14:11:18 | [3fe8681e19ac](https://github.com/tldr-pages/tldr/commit/3fe8681e19acf79351509fb46b1988a0ab64397f)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

