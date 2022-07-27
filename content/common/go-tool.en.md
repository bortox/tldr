---
author: ['Joseph Bane']
date: 1634505783
title: "go tool, TLDR Pages"
description: "go tool, Run a specific Go tool or command."
categories: "common"
---
> Execute a Go command as a stand-alone binary, typically for debugging.

> More information: <https://pkg.go.dev/cmd/go#hdr-Run_specified_go_tool>.

- List available tools:

```bash
go tool
```

- Run the go link tool:

```bash
go tool link path/to/main.o
```

- Print the command that would be executed, but do not execute it (similar to `whereis`):

```bash
go tool -n command arguments
```

- Display documentation for a specified tool:

```bash
go tool command --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joseph Bane](mailto:havocbane@users.noreply.github.com) | go-tool: add page (#6998) | 2021-10-17T23:23:03 | [30ea44a60a4b](https://github.com/tldr-pages/tldr/commit/30ea44a60a4bb4d3272aa3a1ce81e1556602dd2c)

