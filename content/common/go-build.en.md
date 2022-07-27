---
author: ['会有猫的', 'CleanMachine1', 'gonejack']
date: 1641097856
title: "go build, TLDR Pages"
description: "go build, Compile Go sources."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Compile_packages_and_dependencies>.

- Compile a 'package main' file (output will be the filename without extension):

```bash
go build path/to/main.go
```

- Compile, specifying the output filename:

```bash
go build -o path/to/binary path/to/source.go
```

- Compile a package:

```bash
go build -o path/to/binary path/to/package
```

- Compile a main package into an executable, enabling data race detection:

```bash
go build -race -o path/to/executable path/to/main/package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | go-build: add clarity (#7438) | 2022-01-02T05:30:56 | [c13a79e2d98d](https://github.com/tldr-pages/tldr/commit/c13a79e2d98dde12d41beb27c6cc69c84b6e57f6)
[会有猫的](mailto:igonejack@gmail.com) | go-*: apply additional suggestions Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-21T13:33:55 | [4cac843cae95](https://github.com/tldr-pages/tldr/commit/4cac843cae95c7a2aa382595fa4f0837724468bc)
[gonejack](mailto:igonejack@gmail.com) | go-build: apply suggestions Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:23 | [ae117a5437cd](https://github.com/tldr-pages/tldr/commit/ae117a5437cdf3ac3563ff4801566f9ed284aae3)
[gonejack](mailto:igonejack@gmail.com) | go-build: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:23 | [799b2d39ed2c](https://github.com/tldr-pages/tldr/commit/799b2d39ed2c33864072fbb46381352cc5612773)

