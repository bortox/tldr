---
author: ['Ravern Koh', 'pxgamer', 'teeteejo']
date: 1602256468
title: "dep, TLDR Pages"
description: "dep, A CLI tool for deployment of PHP applications."
categories: "common"
---
> Note: The Go command `dep` with the same name is deprecated and archived.

> More information: <https://deployer.org>.

- Interactively initialize deployer in the local path (use a framework template with `--template={{template}}`):

```bash
dep init
```

- Deploy an application to a remote host:

```bash
dep deploy hostname
```

- Rollback to the previous working release:

```bash
dep rollback
```

- Connect to a remote host via ssh:

```bash
dep ssh hostname
```

- List commands:

```bash
dep list
```

- Run any arbitrary command on the remote hosts:

```bash
dep run "command"
```

- Display help for a command:

```bash
dep help command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[teeteejo](mailto:72230915+teeteejo@users.noreply.github.com) | dep: replace page (#4476) Replace Go's retired `dep` command with the PHP deployment command from https://deployer.org Ref: [...] | 2020-10-09T17:14:28 | [de8cb1174e98](https://github.com/tldr-pages/tldr/commit/de8cb1174e9849ba5b33626613a6373b64aa704d)
[pxgamer](mailto:owzie123@gmail.com) | dep: add link to homepage | 2019-06-09T06:54:24 | [06d7168fbfb4](https://github.com/tldr-pages/tldr/commit/06d7168fbfb41f79e6b3c922104701d67fb2edd5)
[Ravern Koh](mailto:22592318+ravernkoh@users.noreply.github.com) | dep: add page (#1796) | 2017-12-13T17:18:16 | [aaba5c5b1282](https://github.com/tldr-pages/tldr/commit/aaba5c5b1282a5b28158e137ee8e8d153b69741c)

