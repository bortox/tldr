---
author: ['marchersimon']
date: 1631539482
title: "compgen, TLDR Pages"
description: "compgen, A built-in command for auto-completion in Bash, which is called on pressing TAB key twice."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/bash.html#index-compgen>.

- List all commands that you could run:

```bash
compgen -c
```

- List all aliases:

```bash
compgen -a
```

- List all functions that you could run:

```bash
compgen -A function
```

- Show shell reserved keywords:

```bash
compgen -k
```

- See all available commands/aliases starting with 'ls':

```bash
compgen -ac ls
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

