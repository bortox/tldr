---
author: ['HG00', 'Lucas Gabriel Schneider', 'Emily Grace Seville']
date: 1647882468
title: "ctrlaltdel, TLDR Pages"
description: "ctrlaltdel, Utility to control what happens when CTRL+ALT+DEL is pressed."
categories: "linux"
---
> More information: <https://manned.org/ctrlaltdel>.

- Get current setting:

```bash
ctrlaltdel
```

- Set CTRL+ALT+DEL to reboot immediately, without any preparation:

```bash
sudo ctrlaltdel hard
```

- Set CTRL+ALT+DEL to reboot "normally", giving processes a chance to exit first (send SIGINT to PID1):

```bash
sudo ctrlaltdel soft
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[HG00](mailto:HG00@users.noreply.github.com) | ctrlaltdel: add page (#3323) | 2019-10-05T00:24:36 | [c82f1e5497d2](https://github.com/tldr-pages/tldr/commit/c82f1e5497d26799b88b9837fe976e4424158347)

