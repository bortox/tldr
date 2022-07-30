---
author: ['ambirdsall-gogo', 'lakhininenina']
date: 1655235712
title: "popd"
description: "popd, Remove a directory placed on the directory stack via the pushd shell built-in."
categories: "common"
---
> See also `pushd` to place a directory on the stack and `dirs` to display directory stack contents.

> More information: <https://www.gnu.org/software/bash/manual/html_node/Directory-Stack-Builtins.html>.

- Remove the top directory from the stack and cd to it:

```bash
popd
```

- Remove the Nth directory (starting from zero to the left from the list printed with `dirs`):

```bash
popd +N
```

- Remove the Nth directory (starting from zero to the right from the list printed with `dirs`):

```bash
popd -N
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lakhininenina](mailto:99631909+lakhininenina@users.noreply.github.com) | popd: add more information link (#8129) | 2022-06-14T21:41:52 | [955fc500415a](https://github.com/tldr-pages/tldr/commit/955fc500415ae319b08902cfdd28cce2fc47830c)
[ambirdsall-gogo](mailto:61211417+ambirdsall-gogo@users.noreply.github.com) | Reference dirs builtin in pushd/popd (#5759) | 2021-04-16T01:53:14 | [cee4489f56d6](https://github.com/tldr-pages/tldr/commit/cee4489f56d64ee35396d89fb5ebdc12f2120ae9)

