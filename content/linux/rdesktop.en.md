---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'Seth Falco', 'Xiang Wang']
date: 1647882468
title: "rdesktop"
description: "rdesktop, Remote Desktop Protocol client."
categories: "linux"
---
> It can be used to connect the remote computer using the RDP protocol.

> More information: <https://manned.org/rdesktop>.

- Connect to a remote computer (default port is 3389):

```bash
rdesktop -u username -p password host:port
```

- Simple Examples:

```bash
rdesktop -u Administrator -p passwd123 192.168.1.111:3389
```

- Connect to a remote computer with full screen (press `Ctrl + Alt + Enter` to exist):

```bash
rdesktop -u username -p password -f host:port
```

- Use the customed resolution (use the letter 'x' between the number):

```bash
rdesktop -u username -p password -g 1366x768 host:port
```

- Connect to a remote computer using domain user:

```bash
rdesktop -u username -p password -d domainname host:port
```

- Use the 16-bit color (speed up):

```bash
rdesktop -u username -p password -a 16 host:port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Xiang Wang](mailto:ramwin@qq.com) | add the page of rdesktop command | 2016-09-15T19:31:42 | [45de439ec37d](https://github.com/tldr-pages/tldr/commit/45de439ec37da286e40406daa88acaf2562732ab)

