---
author: ['bl-ue']
date: 1618082329
title: "xonsh, TLDR Pages"
description: "xonsh, Python-powered, cross-platform, Unix-gazing shell."
categories: "common"
---
> Write and mix sh/Python code in Xonsh (pronounced conch).

> More information: <https://xon.sh>.

- Start an interactive shell session:

```bash
xonsh
```

- Execute a single command and then exit:

```bash
xonsh -c "command"
```

- Run commands from a script file and then exit:

```bash
xonsh path/to/script_file.xonsh
```

- Define environment variables for the shell process:

```bash
xonsh -Dname1=value1 -Dname2=value2
```

- Load the specified `.xonsh` or `.json` configuration files:

```bash
xonsh --rc path/to/file1.xonsh path/to/file2.json
```

- Skip loading the `.xonshrc` configuration file:

```bash
xonsh --no-rc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | xonsh: add page (#5709) | 2021-04-10T21:18:49 | [413ddfcca800](https://github.com/tldr-pages/tldr/commit/413ddfcca80009d1b39bd8d9a504490a89cd194f)

