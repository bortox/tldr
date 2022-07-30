---
author: ['egilkh', 'Gubolin', 'Srinivasan R', 'derNiklaas', 'Seth Woodworth', 'Ruben Vereecken']
date: 1633404950
title: "wall"
description: "wall, Write a message on the terminals of users currently logged in."
categories: "linux"
---
> More information: <https://manned.org/wall>.

- Send a message:

```bash
echo "message" | wall
```

- Send a message from a file:

```bash
wall file
```

- Send a message with timeout (default 300):

```bash
wall -t seconds file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Seth Woodworth](mailto:seth@sethish.com) | wall: clarify description (#1432) | 2017-07-25T20:55:02 | [9abde0228ef2](https://github.com/tldr-pages/tldr/commit/9abde0228ef28997cfaaf65a3a35b6ddfa04f7e0)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[egilkh](mailto:egilkh@gmail.com) | Make tcpdump, wall and useradd match formatting. | 2014-08-18T08:22:39 | [6ebb0b550b1b](https://github.com/tldr-pages/tldr/commit/6ebb0b550b1b4c430bc47c0f91f02bee996bdcad)
[Gubolin](mailto:gubolin@fantasymail.de) | change message to file | 2014-04-04T09:21:11 | [1fa8e8e8468e](https://github.com/tldr-pages/tldr/commit/1fa8e8e8468e659fbbb7cd735c7277a37bf7813d)
[Gubolin](mailto:gubolin@fantasymail.de) | add wall | 2014-04-04T09:14:57 | [f472b5a8658a](https://github.com/tldr-pages/tldr/commit/f472b5a8658abfee43b7235f5fff727822327f63)

