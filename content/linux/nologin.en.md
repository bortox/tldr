---
author: ['lbonanomi', 'Emily Grace Seville']
date: 1647882468
title: "nologin, TLDR Pages"
description: "nologin, Alternative shell that prevents a user from logging in."
categories: "linux"
---
> More information: <https://manned.org/nologin.5>.

- Set a user's login shell to `nologin` to prevent the user from logging in:

```bash
chsh -s user nologin
```

- Customize message for users with the login shell of `nologin`:

```bash
echo "declined_login_message" > /etc/nologin.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | nologin: add page (#2943) | 2019-04-25T22:51:30 | [16c2b1f24279](https://github.com/tldr-pages/tldr/commit/16c2b1f24279f9670facd5164c16d4a650a24e8c)

