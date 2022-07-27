---
author: ['Marius Gherman', 'Lucas Gabriel Schneider']
date: 1630607629
title: "kexec, TLDR Pages"
description: "kexec, Directly reboot into a new kernel."
categories: "linux"
---
> More information: <https://manned.org/kexec>.

- Load a new kernel:

```bash
kexec -l path/to/kernel --initrd=path/to/initrd --command-line=arguments
```

- Load a new kernel with current boot parameters:

```bash
kexec -l path/to/kernel --initrd=path/to/initrd --reuse-cmdline
```

- Execute a currently loaded kernel:

```bash
kexec -e
```

- Unload current kexec target kernel:

```bash
kexec -u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Marius Gherman](mailto:marius.gherman@gmail.com) | kexec: remove / from preceeding path tokens | 2017-12-08T12:22:47 | [0173dee881f5](https://github.com/tldr-pages/tldr/commit/0173dee881f55bc2ae6a501bf95aaab2bf67ac03)
[Marius Gherman](mailto:marius.gherman@gmail.com) | kexec: add page | 2017-12-07T21:19:17 | [f8adef4b511a](https://github.com/tldr-pages/tldr/commit/f8adef4b511aff8811ef0dd146812dc3da12c5c8)

