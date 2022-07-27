---
author: ['user56441']
date: 1585358900
title: "doas, TLDR Pages"
description: "doas, Executes a command as another user."
categories: "common"
---
> More information: <https://man.openbsd.org/doas>.

- Run a command as root:

```bash
doas command
```

- Run a command as another user:

```bash
doas -u user command
```

- Launch the default shell as root:

```bash
doas -s
```

- Parse a config file and check if the execution of a command as another user is allowed:

```bash
doas -C config_file command
```

- Make `doas` request a password even after it was supplied earlier:

```bash
doas -L
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[user56441](mailto:62631913+user56441@users.noreply.github.com) | doas: add page (#3939) | 2020-03-28T02:28:20 | [5d5bc68fdcf4](https://github.com/tldr-pages/tldr/commit/5d5bc68fdcf4aa5bc5ec3fa792af94110f673d6b)

