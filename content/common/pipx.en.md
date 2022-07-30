---
author: ['bl-ue', 'Anay Nayak']
date: 1607722048
title: "pipx"
description: "pipx, Install and run python applications in isolated environments."
categories: "common"
---
> More information: <https://github.com/pipxproject/pipx>.

- Run an app in a temporary virtual environment:

```bash
pipx run pycowsay moo
```

- Install a package in a virtual environment and add entry points to path:

```bash
pipx install package
```

- List installed packages:

```bash
pipx list
```

- Run an app in a temporary virtual environment with a package name different from the executable:

```bash
pipx run --spec httpx-cli httpx http://www.github.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Anay Nayak](mailto:anaynayak@users.noreply.github.com) | pipx: add page (#4477) | 2020-10-05T13:05:06 | [a3ce094b676c](https://github.com/tldr-pages/tldr/commit/a3ce094b676cd443d818f7d2ff27175c8e461d42)

