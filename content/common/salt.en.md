---
author: ['Amine Hajyoussef', 'lord63', 'Ruben Vereecken', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1559133670
title: "salt, TLDR Pages"
description: "salt, Execute commands and assert state on remote salt minions."
categories: "common"
---
> More information: <https://docs.saltstack.com/ref/cli/salt.html>.

- List connected minions:

```bash
salt '*' test.ping
```

- Execute a highstate on all connected minions:

```bash
salt '*' state.highstate
```

- Upgrade packages using the OS package manager (apt, yum, brew) on a subset of minions:

```bash
salt '*.example.com' pkg.upgrade
```

- Execute an arbitrary command on a particular minion:

```bash
salt 'minion_id' cmd.run "ls "
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | salt: update link to homepage | 2019-05-29T14:41:10 | [253707aa52c6](https://github.com/tldr-pages/tldr/commit/253707aa52c6a4241d4b9826d24e757c5fb5e73b)
[pxgamer](mailto:owzie123@gmail.com) | salt: add link to homepage | 2019-05-29T14:41:10 | [a9c38af06300](https://github.com/tldr-pages/tldr/commit/a9c38af06300c5e2f9cd22b17920a320453510d5)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: standardize domain examples (#3010) This change standardizes URL examples in tldr-pages to use the canonical [...] | 2019-05-13T15:33:05 | [ce642b6c12dd](https://github.com/tldr-pages/tldr/commit/ce642b6c12dd502fbe0360732d637357a1c420bf)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | consistent markup | 2015-12-31T14:11:18 | [3fe8681e19ac](https://github.com/tldr-pages/tldr/commit/3fe8681e19acf79351509fb46b1988a0ab64397f)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[lord63](mailto:lord63.j@gmail.com) | Use markdown for salt, salt-run and zbarimg | 2015-09-22T14:01:11 | [52dd29cb9c2a](https://github.com/tldr-pages/tldr/commit/52dd29cb9c2a6cb2e918993ce7910d48069d0e63)

