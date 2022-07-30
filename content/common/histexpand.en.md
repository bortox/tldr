---
author: ['João Pedro Fonseca Dantas', 'marchersimon']
date: 1625513747
title: "history expansion"
description: "history expansion, Reuse and expand the shell history in `sh`, `bash`, `zsh`, `rbash` and `ksh`."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/html_node/History-Interaction>.

- Run the previous command as root (`!!` is replaced by the previous command):

```bash
sudo !!
```

- Run a command with the last argument of the previous command:

```bash
command !$
```

- Run a command with the first argument of the previous command:

```bash
command !^
```

- Run the Nth command of the history:

```bash
!n
```

- Run the command `n` lines back in the history:

```bash
!-n
```

- Run the most recent command containing `string`:

```bash
!?string?
```

- Run the previous command, replacing `string1` with `string2`:

```bash
^string1^string2^
```

- Perform a history expansion, but print the command that would be run instead of actually running it:

```bash
!-n:p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[João Pedro Fonseca Dantas](mailto:67479090+jopefd@users.noreply.github.com) | histexpand: add `!N` and `!?string?` commands (#6051) | 2021-07-05T21:35:47 | [4f714f14de47](https://github.com/tldr-pages/tldr/commit/4f714f14de4723a341c474eb7d2f543118f4f7cc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | histexpand: edit shells and link (#5721) | 2021-04-09T18:46:37 | [a237d650556c](https://github.com/tldr-pages/tldr/commit/a237d650556c00ea689232b217482a9a0a575758)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | histexpand: add page (#5455) Also add a reference to the new page in bash.md and zsh.md | 2021-04-04T22:07:13 | [03819122c9bc](https://github.com/tldr-pages/tldr/commit/03819122c9bc668750cd8c9a7f8a4a92c615c0e3)

