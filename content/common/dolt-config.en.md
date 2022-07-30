---
author: ['bl-ue', 'Seth Falco']
date: 1629050349
title: "dolt config"
description: "dolt config, Read and write local (per repository) and global (per user) Dolt configuration variables."
categories: "common"
---
> More information: <https://docs.dolthub.com/interfaces/cli#dolt-config>.

- List all local and global configuration options and their values:

```bash
dolt config --list
```

- Display the value of a local or global configuration variable:

```bash
dolt config --get name
```

- Modify the value of a local configuration variable, creating it if it doesn't exist:

```bash
dolt config --add name value
```

- Modify the value of a global configuration variable, creating it if it doesn't exist:

```bash
dolt config --global --add name value
```

- Delete a local configuration variable:

```bash
dolt config --unset name
```

- Delete a global configuration variable:

```bash
dolt config --global --unset name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dolt-config: add page (#5720) | 2021-04-10T21:36:56 | [c30eb1d8b23e](https://github.com/tldr-pages/tldr/commit/c30eb1d8b23e6f4596fa02173fd3a2f6f65a988e)

