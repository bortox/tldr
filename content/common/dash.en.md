---
author: ['bl-ue']
date: 1618409241
title: "dash, TLDR Pages"
description: "dash, Debian Almquist Shell, a modern, POSIX-compliant implementation of `sh` (not Bash-compatible)."
categories: "common"
---
> More information: <https://manned.org/dash>.

- Start an interactive shell session:

```bash
dash
```

- Execute a command and then exit:

```bash
dash -c "command"
```

- Execute a script:

```bash
dash path/to/script.sh
```

- Run commands from a script, printing each command before executing it:

```bash
dash -x path/to/script.sh
```

- Execute commands from a script, stopping at the first error:

```bash
dash -e path/to/script.sh
```

- Read and execute commands from stdin:

```bash
dash -s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bash, dash, fish, ksh, rbash, sh, zsh: refresh (#5714) | 2021-04-14T16:07:21 | [16e4ed5c8993](https://github.com/tldr-pages/tldr/commit/16e4ed5c899393a2563346ddde246e136de801ab)

