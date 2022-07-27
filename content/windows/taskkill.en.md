---
author: ['Lucas Gabriel Schneider', 'Seth Falco', 'Owen Voke']
date: 1629050349
title: "taskkill, TLDR Pages"
description: "taskkill, Terminate a process by its process ID or name."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/taskkill>.

- Terminate a process by its ID:

```bash
taskkill /pid process_id
```

- Terminate a process by its name:

```bash
taskkill /im process_name
```

- Forcefully terminate a specified process:

```bash
taskkill /pid process_id /f
```

- Terminate a process and its child processes:

```bash
taskkill /im process_name /t
```

- Terminate a process on a remote machine:

```bash
taskkill /pid process_id /s remote_name
```

- Display information about the usage of the command:

```bash
taskkill /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | taskkill: add page (#1904) | 2018-01-23T12:44:48 | [973c692236c6](https://github.com/tldr-pages/tldr/commit/973c692236c62d2fcd1625333ec70c8b54403296)

