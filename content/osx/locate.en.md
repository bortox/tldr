---
author: ['Waldir Pimenta', 'Srinivasan R', 'Emily Grace Seville', 'Ruben Vereecken', 'Igor Shubovych', 'Gear J']
date: 1644837703
title: "locate, TLDR Pages"
description: "locate, Find filenames quickly."
categories: "osx"
---
> More information: <https://manned.org/locate>.

- Look for pattern in the database. Note: the database is recomputed periodically (usually weekly or daily):

```bash
locate "pattern"
```

- Look for a file by its exact filename (a pattern containing no globbing characters is interpreted as `*pattern*`):

```bash
locate */filename
```

- Recompute the database. You need to do it if you want to find recently added files:

```bash
sudo /usr/libexec/locate.updatedb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Gear J](mailto:12108619+gearj@users.noreply.github.com) | launchctl, lldb, locate, look: add more information link (#6893) | 2021-10-11T07:08:25 | [fcc03f1e6ff9](https://github.com/tldr-pages/tldr/commit/fcc03f1e6ff9776ca4433447e9859a3c1a42e539)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | osx/locate.md: add exact filename match (#993) * osx/locate.md: add exact filename match * linux/locate.md: add exact filename match | 2016-08-08T09:06:59 | [8127104ccec5](https://github.com/tldr-pages/tldr/commit/8127104ccec53af70975dac31831fe4b7b9aefe1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: locate | 2014-05-08T22:25:52 | [888b33c3d598](https://github.com/tldr-pages/tldr/commit/888b33c3d5982ced49a64f2f47accaa40d47447c)

