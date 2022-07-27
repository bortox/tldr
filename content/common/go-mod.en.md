---
author: ['会有猫的', 'gonejack']
date: 1590060835
title: "go mod, TLDR Pages"
description: "go mod, Module maintenance."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Module_maintenance>.

- Initialize new module in current directory:

```bash
go mod init moduleName
```

- Download modules to local cache:

```bash
go mod download
```

- Add missing and remove unused modules:

```bash
go mod tidy
```

- Verify dependencies have expected content:

```bash
go mod verify
```

- Copy sources of all dependencies into the vendor directory:

```bash
go mod vendor
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[会有猫的](mailto:igonejack@gmail.com) | go-*: apply additional suggestions Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-21T13:33:55 | [4cac843cae95](https://github.com/tldr-pages/tldr/commit/4cac843cae95c7a2aa382595fa4f0837724468bc)
[gonejack](mailto:igonejack@gmail.com) | go-mod: apply suggestions Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:24 | [21a74424c7cf](https://github.com/tldr-pages/tldr/commit/21a74424c7cfaa82fdc9f55a1d00f979ee5cf454)
[gonejack](mailto:igonejack@gmail.com) | go-mod: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:22 | [19d232cbf410](https://github.com/tldr-pages/tldr/commit/19d232cbf410c48fd3bf8123aed08a806f28f080)

