---
author: ['Ruben Vereecken', 'ElectricSquid', 'CleanMachine1', 'rprieto']
date: 1633188723
title: "shutdown, TLDR Pages"
description: "shutdown, Shutdown and reboot the system."
categories: "linux"
---
> More information: <https://manned.org/shutdown.8>.

- Power off (halt) immediately:

```bash
shutdown -h now
```

- Reboot immediately:

```bash
shutdown -r now
```

- Reboot in 5 minutes:

```bash
shutdown -r +5 &
```

- Shutdown at 1:00 pm (Uses 24h clock):

```bash
shutdown -h 13:00
```

- Cancel a pending shutdown/reboot operation:

```bash
shutdown -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | shutdown: add more information link (#6657) | 2021-10-02T17:32:03 | [8fa08fe936ea](https://github.com/tldr-pages/tldr/commit/8fa08fe936eacb9229a1b63ad4f8a346a86723e7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[ElectricSquid](mailto:beastmode25800@gmail.com) | Addition to shutdown.md Added section to indicate how to shutdown at a specific time rather than shutting down X minutes from now | 2015-12-31T06:41:06 | [c9b0b290f98d](https://github.com/tldr-pages/tldr/commit/c9b0b290f98d5875fe7fdc9a4cb3222f148a3ea5)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

