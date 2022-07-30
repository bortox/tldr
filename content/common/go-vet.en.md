---
author: ['Morgan Howard']
date: 1634009484
title: "go vet"
description: "go vet, Check Go source code and report suspicious constructs (e.g. lint your Go source files)."
categories: "common"
---
> Go vet returns a non-zero exit code if problems are found; returns a zero exit code if no problems are found.

> More information: <https://pkg.go.dev/cmd/vet>.

- Check the Go package in the current directory:

```bash
go vet
```

- Check the Go package in the specified path:

```bash
go vet path/to/file_or_directory
```

- List available checks that can be run with go vet:

```bash
go tool vet help
```

- View details and flags for a particular check:

```bash
go tool vet help check_name
```

- Display offending lines plus N lines of surrounding context:

```bash
go vet -c=N
```

- Output analysis and errors in JSON format:

```bash
go vet -json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Morgan Howard](mailto:morganhoward@users.noreply.github.com) | go-vet: add page (#6832) | 2021-10-12T05:31:24 | [b5aa93b2914c](https://github.com/tldr-pages/tldr/commit/b5aa93b2914caa3cec52bf029c9c17e86d8940fb)

