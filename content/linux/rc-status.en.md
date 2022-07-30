---
author: ['Azrael JD', 'Starbeamrainbowlabs']
date: 1643286522
title: "rc-status"
description: "rc-status, Show status info about runlevels."
categories: "linux"
---
> See also `openrc`.

> More information: <https://manned.org/rc-status>.

- Show a summary of services and their status:

```bash
rc-status
```

- Include services in all runlevels in the summary:

```bash
rc-status --all
```

- List services that have crashed:

```bash
rc-status --crashed
```

- List manually started services:

```bash
rc-status --manual
```

- List supervised services:

```bash
rc-status --supervised
```

- Get the current runlevel:

```bash
rc-status --runlevel
```

- List all runlevels:

```bash
rc-status --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | rc-status: add more information link (#7715) | 2022-01-27T13:28:42 | [735d1539d08e](https://github.com/tldr-pages/tldr/commit/735d1539d08e5378dc61df7c38da1d2dcccdfe8d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | openrc, rc-status, rc-service, rc-update: add pages (#3800) * rc-status: add page * openrc: add page * rc-service: add page * rc- [...] | 2020-01-27T14:13:47 | [a0d7c46e801a](https://github.com/tldr-pages/tldr/commit/a0d7c46e801a5d5874eae9a9ec55588863a97483)

