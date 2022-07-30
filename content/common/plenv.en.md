---
author: ['dz-at-tc']
date: 1635600059
title: "plenv"
description: "plenv, Switch between multiple versions of Perl."
categories: "common"
---
> More information: <https://github.com/tokuhirom/plenv>.

- Show the currently selected Perl version and how it was selected:

```bash
plenv version
```

- List all available installed Perl versions:

```bash
plenv versions
```

- Set the global Perl version (used unless a local or shell version takes priority):

```bash
plenv global version
```

- Set the local application-specific Perl version (used in the current directory and all directories below it):

```bash
plenv local version
```

- Set the shell-specific Perl version (used for the current session only):

```bash
plenv shell version
```

- Display help:

```bash
plenv
```

- Display help for a command:

```bash
plenv help command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dz-at-tc](mailto:49352191+dz-at-tc@users.noreply.github.com) | plenv: add page (#7118) | 2021-10-30T15:20:59 | [c39d4cb29f67](https://github.com/tldr-pages/tldr/commit/c39d4cb29f67218f569c26b7e6e5bff37f63d7af)

