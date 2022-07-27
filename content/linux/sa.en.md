---
author: ['Ben Glanton', 'Emily Grace Seville']
date: 1647882468
title: "sa, TLDR Pages"
description: "sa, Summarizes accounting information. Part of the acct package."
categories: "linux"
---
> Shows commands called by users, including basic info on CPU time spent processing and I/O rates.

> More information: <https://manned.org/man/sa.8>.

- Display executable invocations per user (username not displayed):

```bash
sudo sa
```

- Display executable invocations per user, showing responsible usernames:

```bash
sudo sa --print-users
```

- List resources used recently per user:

```bash
sudo sa --user-summary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Ben Glanton](mailto:56129020+glantonb@users.noreply.github.com) | sa: add page (#3315) | 2019-10-10T19:42:19 | [cddc54c7a9b9](https://github.com/tldr-pages/tldr/commit/cddc54c7a9b92be422a32b994046d8246f91be6a)

