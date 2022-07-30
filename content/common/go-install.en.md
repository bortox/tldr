---
author: ['endorama']
date: 1638740487
title: "go install"
description: "go install, Compile and install packages named by the import paths."
categories: "common"
---
> More information: <https://pkg.go.dev/cmd/go#hdr-Compile_and_install_packages_and_dependencies>.

- Compile and install the current package:

```bash
go install
```

- Compile and install a specific local package:

```bash
go install path/to/package
```

- Install the latest version of a program, ignoring `go.mod` in the current directory:

```bash
go install golang.org/x/tools/gopls@latest
```

- Install a program at the version selected by `go.mod` in the current directory:

```bash
go install golang.org/x/tools/gopls
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[endorama](mailto:526307+endorama@users.noreply.github.com) | go-install: add page (#7111) | 2021-12-05T22:41:27 | [6a48a5a31a32](https://github.com/tldr-pages/tldr/commit/6a48a5a31a32d549b221242fe25ad58d8413c400)

