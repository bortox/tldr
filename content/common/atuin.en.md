---
author: ['Adrien Thebo']
date: 1662262188
title: "atuin"
description: "atuin, Store your shell history in a searchable database."
categories: "common"
---
> Optionally sync your encrypted history between machines.

> More information: <https://atuin.sh/docs/overview/introduction/>.

- Install atuin into your shell:

```bash
eval "$(atuin init bash|zsh|fish)"
```

- Import history from the shell default history file:

```bash
atuin import auto
```

- Search shell history for a specific command:

```bash
atuin search command
```

- Register an account on the default sync server:

```bash
atuin register -u username -e email -p password
```

- Login to the default sync server:

```bash
atuin login -u username -p password
```

- Sync history with the sync server:

```bash
atuin sync
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | atuin: add page (#8446) | 2022-09-04T05:29:48 | [dd33c21bcd1d](https://github.com/tldr-pages/tldr/commit/dd33c21bcd1d1322eae51877fedf8c87af33f3e7)

