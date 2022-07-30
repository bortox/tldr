---
author: ['Sasha Khamkov', 'Marco Bonelli', 'derNiklaas', 'Romain Prieto', 'Ruben Vereecken']
date: 1633404950
title: "watch"
description: "watch, Execute a command repeatedly, and monitor the output in full-screen mode."
categories: "linux"
---
> More information: <https://manned.org/watch>.

- Monitor files in the current directory:

```bash
watch ls
```

- Monitor disk space and highlight the changes:

```bash
watch -d df
```

- Monitor "node" processes, refreshing every 3 seconds:

```bash
watch -n 3 "ps aux | grep node"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Sasha Khamkov](mailto:sanusart@gmail.com) | Missing apostrophe Missing apostrophe in monitor "node" processes | 2014-05-04T09:29:14 | [a46d484671c3](https://github.com/tldr-pages/tldr/commit/a46d484671c37fac8e6b3e48d875e3588e51bdd2)
[Romain Prieto](mailto:choicesmade@gmail.com) | Create watch.md | 2014-03-06T03:24:55 | [ec26997a1da0](https://github.com/tldr-pages/tldr/commit/ec26997a1da0cb58ebff9b0bdce070cb9eb5a1de)

