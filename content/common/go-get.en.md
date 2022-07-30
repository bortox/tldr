---
author: ['diver']
date: 1631627113
title: "go get"
description: "go get, Add a dependency package, or download packages in legacy GOPATH mode."
categories: "common"
---
> More information: <https://pkg.go.dev/cmd/go#hdr-Add_dependencies_to_current_module_and_install_them>.

- Add a specified package to `go.mod` in module-mode or install the package in GOPATH-mode:

```bash
go get example.com/pkg
```

- Modify the package with a given version in module-aware mode:

```bash
go get example.com/pkg@v1.2.3
```

- Remove a specified package:

```bash
go get example.com/pkg@none
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[diver](mailto:57475552+gilf3@users.noreply.github.com) | go-get: add page (#6491) | 2021-09-14T15:45:13 | [82d63f39bf2c](https://github.com/tldr-pages/tldr/commit/82d63f39bf2cc063fdae7aea1a6ebbc9d7e38b10)

