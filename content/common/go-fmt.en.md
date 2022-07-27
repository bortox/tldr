---
author: ['Morgan Howard']
date: 1634008046
title: "go fmt, TLDR Pages"
description: "go fmt, Format Go source files."
categories: "common"
---
> Prints the filenames that are changed.

> More information: <https://pkg.go.dev/cmd/go#hdr-Gofmt__reformat__package_sources>.

- Format Go source files in the current directory:

```bash
go fmt
```

- Format a specific Go package in your import path (`$GOPATH/src`):

```bash
go fmt path/to/package
```

- Format the package in the current directory and all subdirectories (note the `...`):

```bash
go fmt ./...
```

- Print what format commands would've been run, without modifying anything:

```bash
go fmt -n
```

- Print which format commands are run as they are run:

```bash
go fmt -x
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Morgan Howard](mailto:morganhoward@users.noreply.github.com) | go-fmt: add page (#6703) | 2021-10-12T05:07:26 | [10420903910c](https://github.com/tldr-pages/tldr/commit/10420903910ce3fbae3596d0979e9db3468a51de)

