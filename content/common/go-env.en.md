---
author: ['会有猫的', 'gonejack']
date: 1590060835
title: "go env, TLDR Pages"
description: "go env, Manage environment variables used by the Go toolchain."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Print_Go_environment_information>.

- Show all environment variables:

```bash
go env
```

- Show a specific environment variable:

```bash
go env GOPATH
```

- Set an environment variable to a value:

```bash
go env -w GOBIN=path/to/directory
```

- Reset an environment variable's value:

```bash
go env -u GOBIN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[会有猫的](mailto:igonejack@gmail.com) | go-*: apply additional suggestions Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-21T13:33:55 | [4cac843cae95](https://github.com/tldr-pages/tldr/commit/4cac843cae95c7a2aa382595fa4f0837724468bc)
[gonejack](mailto:igonejack@gmail.com) | go-env: apply suggestions Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:23 | [e9bd9da77a0c](https://github.com/tldr-pages/tldr/commit/e9bd9da77a0cb90da2d7b16c267817de9f78fca6)
[gonejack](mailto:igonejack@gmail.com) | go-env: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:22 | [16c3791dd9c0](https://github.com/tldr-pages/tldr/commit/16c3791dd9c062ac3897b5849bf5ce07c96dc753)

