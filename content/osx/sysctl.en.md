---
author: ['meowmeowcat', 'Peter Tripp', 'rprieto', 'NashMiao', 'Ruben Vereecken', 'lord63']
date: 1636919159
title: "sysctl"
description: "sysctl, Access kernel state information."
categories: "osx"
---
> More information: <https://ss64.com/osx/sysctl.html>.

- Show all available variables and their values:

```bash
sysctl -a
```

- Show Apple model identifier:

```bash
sysctl -n hw.model
```

- Show CPU model:

```bash
sysctl -n machdep.cpu.brand_string
```

- Show available CPU features (MMX, SSE, SSE2, SSE3, AES, etc):

```bash
sysctl -n machdep.cpu.features
```

- Set a changeable kernel state variable:

```bash
sysctl -w section.tunable=value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[NashMiao](mailto:18191964+NashMiao@users.noreply.github.com) | sysctl: fix typo (#4184) * Fix wrong option * Update sysctl.md | 2020-07-16T20:44:50 | [7c4aab2566fe](https://github.com/tldr-pages/tldr/commit/7c4aab2566fe77e489bf61877a34f076e06e7422)
[Peter Tripp](mailto:petertripp@gmail.com) | Sysctl: Condense by removing explicit maxfiles example. | 2016-01-20T12:46:22 | [35a697f99c7c](https://github.com/tldr-pages/tldr/commit/35a697f99c7cc6ebb2db8143ca9b853c1f676601)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for osx | 2015-10-22T09:33:24 | [3e1df9f818b1](https://github.com/tldr-pages/tldr/commit/3e1df9f818b1c0751b2db2379388378df85efa19)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

