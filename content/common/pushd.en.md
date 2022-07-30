---
author: ['Juan Martin Enriquez', 'ambirdsall-gogo', 'Kwang Kim', 'Ruben Vereecken']
date: 1618530794
title: "pushd"
description: "pushd, Place a directory on a stack so it can be accessed later."
categories: "common"
---
> See also `popd` to switch back to original directory and `dirs` to display directory stack contents.

- Switch to directory and push it on the stack:

```bash
pushd directory
```

- Switch first and second directories on the stack:

```bash
pushd
```

- Rotate stack by making the 5th element the top of the stack:

```bash
pushd +4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ambirdsall-gogo](mailto:61211417+ambirdsall-gogo@users.noreply.github.com) | Reference dirs builtin in pushd/popd (#5759) | 2021-04-16T01:53:14 | [cee4489f56d6](https://github.com/tldr-pages/tldr/commit/cee4489f56d64ee35396d89fb5ebdc12f2120ae9)
[Juan Martin Enriquez](mailto:juanenriquez@gmail.com) | pushd: added platform specific examples in windows, osx and linux. Removed from common. | 2017-10-09T05:09:49 | [8bdd25d67fc4](https://github.com/tldr-pages/tldr/commit/8bdd25d67fc45e035a121ebdd8f051f07996cb18)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Kwang Kim](mailto:kkim@ondeck.com) | Moved pushd.md to common folder | 2014-08-07T19:38:25 | [004807a10e29](https://github.com/tldr-pages/tldr/commit/004807a10e293973a5533f55ad87d91e3c873001)

