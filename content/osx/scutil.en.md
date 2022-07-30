---
author: ['meowmeowcat', 'ramz']
date: 1636919159
title: "scutil"
description: "scutil, Manage system configuration parameters."
categories: "osx"
---
> Necessitates to be root when setting configuration.

> More information: <https://ss64.com/osx/scutil.html>.

- Display DNS Configuration:

```bash
scutil --dns
```

- Display proxy configuration:

```bash
scutil --proxy
```

- Get computer name:

```bash
scutil --get ComputerName
```

- Set computer name:

```bash
sudo scutil --set ComputerName computer_name
```

- Get hostname:

```bash
scutil --get HostName
```

- Set hostname:

```bash
scutil --set HostName hostname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[ramz](mailto:ramzthecoder@gmail.com) | scutil: add page (#1761) | 2017-12-06T17:11:23 | [39c88437d09b](https://github.com/tldr-pages/tldr/commit/39c88437d09bdded4b3bed6f1939367297042875)

