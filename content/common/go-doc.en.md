---
author: ['gonejack', '会有猫的']
date: 1590060835
title: "go doc"
description: "go doc, Show documentation for a package or symbol."
categories: "common"
---
> More information: <https://golang.org/cmd/go/#hdr-Show_documentation_for_package_or_symbol>.

- Show documentation for the current package:

```bash
go doc
```

- Show package documentation and exported symbols:

```bash
go doc encoding/json
```

- Show also documentation of symbols:

```bash
go doc -all encoding/json
```

- Show also sources:

```bash
go doc -all -src encoding/json
```

- Show a specific symbol:

```bash
go doc -all -src encoding/json.Number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[会有猫的](mailto:igonejack@gmail.com) | go-*: apply additional suggestions Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-21T13:33:55 | [4cac843cae95](https://github.com/tldr-pages/tldr/commit/4cac843cae95c7a2aa382595fa4f0837724468bc)
[gonejack](mailto:igonejack@gmail.com) | go-doc: apply suggestion Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:23 | [ea24f0643a5b](https://github.com/tldr-pages/tldr/commit/ea24f0643a5bb07528eca728f6b9c37a41e40fde)
[gonejack](mailto:igonejack@gmail.com) | go-doc: add page (#4003) Signed-off-by: gonejack <igonejack@gmail.com> | 2020-05-21T13:30:22 | [fe8743a0674e](https://github.com/tldr-pages/tldr/commit/fe8743a0674e45bf05598b5e8a3b143c365866ab)

