---
author: ['Kelly Brazil']
date: 1591283117
title: "jc, TLDR Pages"
description: "jc, A utility to convert the output of multiple commands to JSON."
categories: "common"
---
> More information: <https://github.com/kellyjonbrazil/jc>.

- Convert command output to JSON via pipe:

```bash
ifconfig | jc --ifconfig
```

- Convert command output to JSON via magic syntax:

```bash
jc ifconfig
```

- Output pretty JSON via pipe:

```bash
ifconfig | jc --ifconfig -p
```

- Output pretty JSON via magic syntax:

```bash
jc -p ifconfig
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kelly Brazil](mailto:kellyjonbrazil@gmail.com) | jc: add page (#4089) | 2020-06-04T17:05:17 | [b4c25483c965](https://github.com/tldr-pages/tldr/commit/b4c25483c96542b9f58c0647cc2b26ee58467638)

