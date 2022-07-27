---
author: ['Augustin Grigorov', 'Agniva De Sarker', 'pxgamer', 'Max Strübing', 'marchersimon']
date: 1631521281
title: "go, TLDR Pages"
description: "go, Tool for managing go source code."
categories: "common"
---
> Some subcommands such as `go build` have their own usage documentation.

> More information: <https://golang.org>.

- Download and install a package, specified by its import path:

```bash
go get package_path
```

- Compile and run a source file (it has to contain a `main` package):

```bash
go run file.go
```

- Compile a source file into a named executable:

```bash
go build -o executable file.go
```

- Compile the package present in the current directory:

```bash
go build
```

- Execute all test cases of the current package (files have to end with `_test.go`):

```bash
go test
```

- Compile and install the current package:

```bash
go install
```

- Initialize a new module in the current directory:

```bash
go mod init module_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Augustin Grigorov](mailto:AugustinGrigorov@users.noreply.github.com) | go: add go modules (#3935) * Add GO modules init command Add command for initialising a new GO module. More about go modules: [...] | 2020-03-27T13:47:07 | [72114be85736](https://github.com/tldr-pages/tldr/commit/72114be857365fba6e6583e297786280f24aa416)
[pxgamer](mailto:owzie123@gmail.com) | go: add link to homepage | 2019-06-07T23:58:59 | [01c1f02c641f](https://github.com/tldr-pages/tldr/commit/01c1f02c641f541ad87fe0f51e71164c0d23f50c)
[Max Strübing](mailto:mxstrbng@gmail.com) | go: add named executable example (#1506) | 2017-09-28T11:20:26 | [0639876c42c3](https://github.com/tldr-pages/tldr/commit/0639876c42c3166183ebb93626ef72a89b1a2c08)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | go: add page (#1085) | 2016-09-24T18:03:48 | [b0cc68425b65](https://github.com/tldr-pages/tldr/commit/b0cc68425b65663c36328f1274baf665347d7359)

