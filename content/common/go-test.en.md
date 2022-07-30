---
author: ['Davi', 'Nicolas Kosinski']
date: 1646654695
title: "go test"
description: "go test, Tests Go packages (files have to end with `_test.go`)."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Testing_flags>.

- Test the package found in the current directory:

```bash
go test
```

- [v]erbosely test the package in the current directory:

```bash
go test -v
```

- Test the packages in the current directory and all subdirectories (note the `...`):

```bash
go test -v ./...
```

- Test the package in the current directory and run all benchmarks:

```bash
go test -v -bench .
```

- Test the package in the current directory and run all benchmarks for 50 seconds:

```bash
go test -v -bench . -benchtime 50s
```

- Test the package with coverage analysis:

```bash
go test -cover
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | go-test: add -cover example (#7858) | 2022-03-07T13:04:55 | [fa9cbe265b5c](https://github.com/tldr-pages/tldr/commit/fa9cbe265b5c14614d3ae60233856e7a411254b9)
[Davi](mailto:davi@agst.dev) | go-test: add page (#6130) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-06-17T04:07:59 | [f60e542813d1](https://github.com/tldr-pages/tldr/commit/f60e542813d119878c87e6c85d8486b02897f809)

