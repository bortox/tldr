---
author: ['Aakash Sharma', 'Seth Falco']
date: 1653750887
title: "xev, TLDR Pages"
description: "xev, Print contents of X events."
categories: "common"
---
> More information: <https://gitlab.freedesktop.org/xorg/app/xev>.

- Monitor all occurring X events:

```bash
xev
```

- Monitor all X events of the root window instead of creating a new one:

```bash
xev -root
```

- Monitor all X events of a particular window:

```bash
xev -id window_id
```

- Monitor X events from a given category (can be specified multiple times):

```bash
xev -event event_category
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | xev: fix typo (#8107) | 2022-05-28T17:14:47 | [73b6fd21fdbc](https://github.com/tldr-pages/tldr/commit/73b6fd21fdbcd0f9a48f7c30da31310ee39c0d39)
[Aakash Sharma](mailto:60808802+AakashSharma7269@users.noreply.github.com) | xev: add page (#6548) | 2021-09-18T16:16:04 | [2dd1546512a5](https://github.com/tldr-pages/tldr/commit/2dd1546512a5a057e87c9aaa59b2811500b46d8e)

