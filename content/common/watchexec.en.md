---
author: ['WnndGws']
date: 1590608868
title: "watchexec, TLDR Pages"
description: "watchexec, Run arbitrary commands when files change."
categories: "common"
---
> More information: <https://github.com/watchexec/watchexec>.

- Call `ls -la` when any file in the current directory changes:

```bash
watchexec -- ls -la
```

- Run `make` when any JavaScript, CSS and HTML files in the current directory change:

```bash
watchexec --exts js,css,html make
```

- Run `make` when any file in the `lib` or `src` subdirectories change:

```bash
watchexec --watch lib --watch src make
```

- Call/restart `my_server` when any file in the current directory change, sending `SIGKILL` to stop the child process:

```bash
watchexec --restart --signal SIGKILL my_server
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[WnndGws](mailto:WnndGws@users.noreply.github.com) | watchexec: add page (#4061) | 2020-05-27T21:47:48 | [a5eca83ccae8](https://github.com/tldr-pages/tldr/commit/a5eca83ccae8cbd3412a43b742e3e73e0c20de0e)

