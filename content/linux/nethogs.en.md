---
author: ['Owen Voke', 'SeverinFuerbringer', 'Ruben Vereecken']
date: 1609243325
title: "nethogs"
description: "nethogs, Monitor bandwidth usage per process."
categories: "linux"
---
> More information: <https://github.com/raboof/nethogs>.

- Start nethogs as root (default device is eth0):

```bash
sudo nethogs
```

- Monitor bandwidth on specific device:

```bash
sudo nethogs device
```

- Monitor bandwidth on multiple devices:

```bash
sudo nethogs device1 device2
```

- Specify refresh rate:

```bash
sudo nethogs -t seconds
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | nethogs: add more information link | 2020-12-29T13:02:05 | [0a671b44022b](https://github.com/tldr-pages/tldr/commit/0a671b44022baa35393984b1771440f67c0f3fe7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[SeverinFuerbringer](mailto:severin@protonmail.ch) | nethogs: add page Added sudo | 2016-01-06T08:58:08 | [875e59f44b16](https://github.com/tldr-pages/tldr/commit/875e59f44b1685c1b7308191a654d05bdbcc4999)

