---
author: ['Fabio Serragnoli', 'derNiklaas', 'Hayden Schiff']
date: 1655813066
title: "watch, TLDR Pages"
description: "watch, Execute a program periodically, showing output fullscreen."
categories: "common"
---
> More information: <https://manned.org/watch>.

- Repeatedly run a command and show the result:

```bash
watch command
```

- Re-run a command every 60 seconds:

```bash
watch -n 60 command
```

- Monitor the contents of a directory, highlighting differences as they appear:

```bash
watch -d ls -l
```

- Repeatedly run a pipeline and show the result:

```bash
watch 'command_1 | command_2 | command_3'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fabio Serragnoli](mailto:fabio@serragnoli.com) | watch: add pipeline example (#8085) | 2022-06-21T14:04:26 | [85a9e8993e2f](https://github.com/tldr-pages/tldr/commit/85a9e8993e2f721e34d7b13b4d60630639b9e6ac)
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Hayden Schiff](mailto:oxguy3@gmail.com) | watch: "changes"-->"differences" per waldyrious' suggestion in comments of #707 | 2016-01-22T02:37:36 | [5faa753d8fd3](https://github.com/tldr-pages/tldr/commit/5faa753d8fd35aaac6001580145f883c5aedc2d0)
[Hayden Schiff](mailto:oxguy3@gmail.com) | watch: add page | 2016-01-22T01:13:27 | [5b175dfb89a7](https://github.com/tldr-pages/tldr/commit/5b175dfb89a76cf54b8e54b89f07eff0edd0c3a6)

