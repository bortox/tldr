---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "tasklist"
description: "tasklist, Display a list of currently running processes on a local or remote machine."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tasklist>.

- Display currently running processes:

```bash
tasklist
```

- Display running processes in a specified output format:

```bash
tasklist /fo table|list|csv
```

- Display running processes using the specified `.exe` or `.dll` file name:

```bash
tasklist /m module_pattern
```

- Display processes running on a remote machine:

```bash
tasklist /s remote_name /u username /p password
```

- Display services using each process:

```bash
tasklist /svc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | tasklist: add page (#1934) | 2018-02-03T11:29:20 | [d08d8603eca9](https://github.com/tldr-pages/tldr/commit/d08d8603eca993e1c26366a2a03e99e0de5419ba)

