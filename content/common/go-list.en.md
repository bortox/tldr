---
author: ['gonejack', 'Seth Falco']
date: 1629050349
title: "go list"
description: "go list, List packages or modules."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-List_packages_or_modules>.

- List packages:

```bash
go list ./...
```

- List standard packages:

```bash
go list std
```

- List packages in JSON format:

```bash
go list -json time net/http
```

- List module dependencies and available updates:

```bash
go list -m -u all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[gonejack](mailto:igonejack@gmail.com) | go-list: apply suggestions Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:24 | [8421b10d30c0](https://github.com/tldr-pages/tldr/commit/8421b10d30c0dfd2a36ea84dde54249de4590e28)
[gonejack](mailto:igonejack@gmail.com) | go-list: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:22 | [f289daca9e02](https://github.com/tldr-pages/tldr/commit/f289daca9e02b47658d90c13ae0804228614127c)

