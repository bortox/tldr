---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Seth Falco', 'Owen Voke']
date: 1629050349
title: "whoami, TLDR Pages"
description: "whoami, Display details about the current user."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/whoami>.

- Display the username of the current user:

```bash
whoami
```

- Display the groups that the current user is a member of:

```bash
whoami /groups
```

- Display the privileges of the current user:

```bash
whoami /priv
```

- Display the user principal name (UPN) of the current user:

```bash
whoami /upn
```

- Display the logon ID of the current user:

```bash
whoami /logonid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | whoami: add page | 2018-07-11T08:53:22 | [e6cc1dfd02c7](https://github.com/tldr-pages/tldr/commit/e6cc1dfd02c763e10dfb43672ed02fbac57f2994)

