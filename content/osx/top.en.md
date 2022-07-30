---
author: ['Ruben Vereecken', 'Igor Shubovych', 'meowmeowcat', 'Agniva De Sarker']
date: 1642165187
title: "top"
description: "top, Display dynamic real-time information about running processes."
categories: "osx"
---
> More information: <https://ss64.com/osx/top.html>.

- Start top, all options are available in the interface:

```bash
top
```

- Start top sorting processes by internal memory size (default order - process ID):

```bash
top -o mem
```

- Start top sorting processes first by CPU, then by running time:

```bash
top -o cpu -O time
```

- Start top displaying only processes owned by given user:

```bash
top -user user_name
```

- Get help about interactive commands:

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | textutil, top: add link (#7629) | 2022-01-14T13:59:47 | [e2f4d81f6bd4](https://github.com/tldr-pages/tldr/commit/e2f4d81f6bd48fe667d0659b5cb165a2244c9f54)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | top: removing batch mode examples, because it is not obvious | 2015-12-09T18:19:27 | [8bf010111a68](https://github.com/tldr-pages/tldr/commit/8bf010111a680c3298b7e1350a71addd5cd90b5a)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Added top command for Linux and OSX | 2015-12-09T18:19:27 | [63472222b831](https://github.com/tldr-pages/tldr/commit/63472222b8311001bf1b8ee3dbb623efa2df6bef)

