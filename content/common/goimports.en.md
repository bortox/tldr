---
author: ['sebastientinel', 'Koung']
date: 1603905583
title: "goimports"
description: "goimports, Updates Go import lines, adding missing ones and removing unreferenced ones."
categories: "common"
---
> More information: <https://godoc.org/golang.org/x/tools/cmd/goimports>.

- Display the completed import source file:

```bash
goimports file.go
```

- Write the result back to the source file instead of the standard output:

```bash
goimports -w file.go
```

- Display diffs and write the result back to the source file:

```bash
goimports -w -d file.go
```

- Set the import prefix string after 3rd-party packages (comma-separated list):

```bash
goimports -local path/to/package file.go
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Koung](mailto:20951663+koungkub@users.noreply.github.com) | goimports: add page (#3308) | 2019-10-10T20:11:18 | [93538ed58d55](https://github.com/tldr-pages/tldr/commit/93538ed58d55fb95be1f74737008204ff97798fe)

