---
author: ['gonejack', '会有猫的']
date: 1590060835
title: "go clean"
description: "go clean, Remove object files and cached files."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Remove_object_files_and_cached_files>.

- Print the remove commands instead of actually removing anything:

```bash
go clean -n
```

- Delete the build cache:

```bash
go clean -cache
```

- Delete all cached test results:

```bash
go clean -testcache
```

- Delete the module cache:

```bash
go clean -modcache
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[会有猫的](mailto:igonejack@gmail.com) | go-*: apply additional suggestions Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-21T13:33:55 | [4cac843cae95](https://github.com/tldr-pages/tldr/commit/4cac843cae95c7a2aa382595fa4f0837724468bc)
[gonejack](mailto:igonejack@gmail.com) | go-clean: apply suggestions Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:23 | [0f22991cb6eb](https://github.com/tldr-pages/tldr/commit/0f22991cb6ebb51db5bbb688f5b5d3a09e986c97)
[gonejack](mailto:igonejack@gmail.com) | go-clean: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:22 | [be4d64baf29d](https://github.com/tldr-pages/tldr/commit/be4d64baf29d6db7a9f79e486155d8c70da9916c)

