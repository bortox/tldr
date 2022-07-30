---
author: ['Axel Navarro']
date: 1634206421
title: "husky"
description: "husky, Native Git hooks made easy."
categories: "common"
---
> More information: <https://typicode.github.io/husky>.

- Install Husky in the current directory:

```bash
husky install
```

- Install Husky into a specific directory:

```bash
husky install path/to/directory
```

- Set a specific command as a `pre-push` hook for Git:

```bash
husky set .husky/pre-push "command command_arguments"
```

- Add a specific command to the current `pre-commit` hook:

```bash
husky add .husky/pre-commit "command command_arguments"
```

- Uninstall Husky hooks from the current directory:

```bash
husky uninstall
```

- Display help:

```bash
husky
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | husky: add page (#6999) | 2021-10-14T12:13:41 | [65b5648f4b7b](https://github.com/tldr-pages/tldr/commit/65b5648f4b7b5162d3940050c656abca36907064)

