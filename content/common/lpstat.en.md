---
author: ['Igor Shubovych', 'Ruben Vereecken', 'lincc']
date: 1632422063
title: "lpstat, TLDR Pages"
description: "lpstat, Show status information about printers."
categories: "common"
---
> More information: <https://manned.org/lpstat>.

- List printers present on the machine and whether they are enabled for printing:

```bash
lpstat -p
```

- Show the default printer:

```bash
lpstat -d
```

- Display all available status information:

```bash
lpstat -t
```

- Show a list of print jobs queued by the specified user:

```bash
lpstat -u user
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Update lpstat command: add 2 examples | 2015-12-14T10:45:30 | [fda4d79fb61f](https://github.com/tldr-pages/tldr/commit/fda4d79fb61f09015d64c35d85c47a5180be50f1)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | #321: add lp and lpstat commands (kudos to @Qtrain) | 2015-12-01T03:44:01 | [08b7e1c0cdda](https://github.com/tldr-pages/tldr/commit/08b7e1c0cdda3e3af4adee0d1735ba2fdf9def0a)

