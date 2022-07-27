---
author: ['Pierre Rudloff']
date: 1575044022
title: "xvfb-run, TLDR Pages"
description: "xvfb-run, Run a command in a virtual X server environment."
categories: "linux"
---
> More information: <https://www.x.org/wiki/>.

- Run the specified command in a virtual X server:

```bash
xvfb-run command
```

- Try to get a free server number, if the default (99) is not available:

```bash
xvfb-run --auto-servernum command
```

- Pass arguments to the Xvfb server:

```bash
xvfb-run --server-args "-screen 0 1024x768x24" command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | xvfb-run: add page (#3615) | 2019-11-29T17:13:42 | [270a93b9defd](https://github.com/tldr-pages/tldr/commit/270a93b9defd8c4abf680ca3f79e9c9e99bdf425)

