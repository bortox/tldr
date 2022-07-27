---
author: ['git-em']
date: 1646799539
title: "setsid, TLDR Pages"
description: "setsid, Run a program in a new session if the calling process is not a process group leader."
categories: "linux"
---
> The created session is by default not controlled by the current terminal.

> More information: <https://manned.org/setsid>.

- Run a program in a new session:

```bash
setsid program
```

- Run a program in a new session discarding the resulting output and error:

```bash
setsid program > /dev/null 2>&1
```

- Run a program creating a new process:

```bash
setsid --fork program
```

- Return the exit code of a program as the exit code of setsid when the program exits:

```bash
setsid --wait program
```

- Run a program in a new session setting the current terminal as the controlling terminal:

```bash
setsid --ctty program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | setsid: add page (#7841) * setsid: add page * Use "exit code" instead of "return value" Co-authored-by: pixel <chrissx@chrissx.de> Co- [...] | 2022-03-09T05:18:59 | [c5309c0ab8c6](https://github.com/tldr-pages/tldr/commit/c5309c0ab8c68e949994ae1189543b895c6f30ef)

