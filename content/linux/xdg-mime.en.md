---
author: ['aaaawwWWWwwwwWWW', 'Seth Falco']
date: 1629050349
title: "xdg-mime"
description: "xdg-mime, Query and manage MIME types according to the XDG standard."
categories: "linux"
---
> More information: <https://portland.freedesktop.org/doc/xdg-mime.html>.

- Display the MIME type of a file:

```bash
xdg-mime query filetype path/to/file
```

- Display the default application for opening PNGs:

```bash
xdg-mime query default image/png
```

- Display the default application for opening a specific file:

```bash
xdg-mime query default $(xdg-mime query filetype path/to/file)
```

- Set imv as the default application for opening PNG and JPEG images:

```bash
xdg-mime default imv.desktop image/png image/jpeg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[aaaawwWWWwwwwWWW](mailto:73749744+aaaawwWWWwwwwWWW@users.noreply.github.com) | xdg-mime: add page (#4998) | 2020-11-30T14:42:28 | [890d7e3553b9](https://github.com/tldr-pages/tldr/commit/890d7e3553b9813f8bed6d8b6d6757e618e0147b)

