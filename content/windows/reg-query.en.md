---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "reg query, TLDR Pages"
description: "reg query, Display the values of keys and sub keys in the registry."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-query>.

- Display all values of a key:

```bash
reg query key_name
```

- Display a specific value of a key:

```bash
reg query key_name /v value
```

- Display all values of a key and its sub keys:

```bash
reg query key_name /s
```

- Search for keys and values matching a specific pattern:

```bash
reg query key_name /f "query_pattern"
```

- Display a value of a key matching a specified data type:

```bash
reg query key_name /t type
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | reg-query: add page (#1909) | 2018-01-22T04:24:20 | [6d7afc1982f6](https://github.com/tldr-pages/tldr/commit/6d7afc1982f6a70ccfe0796c2c98d3cd44fac159)

