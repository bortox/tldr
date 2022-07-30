---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "reg compare"
description: "reg compare, Compare keys and their values in the registry."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-compare>.

- Compare all values under a specific key with a second key:

```bash
reg compare first_key_name second_key_name
```

- Compare a specific value under two keys:

```bash
reg compare first_key_name second_key_name /v value
```

- Compare all sub keys and values for two keys:

```bash
reg compare first_key_name second_key_name /s
```

- Only output the matches between the specified keys:

```bash
reg compare first_key_name second_key_name /os
```

- Output the differences and matches between the specified keys:

```bash
reg compare first_key_name second_key_name /oa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | reg-compare: add page (#1923) | 2018-01-25T11:11:44 | [29a6f5979c06](https://github.com/tldr-pages/tldr/commit/29a6f5979c06ca68902cb7544279ad43aabb5e71)

