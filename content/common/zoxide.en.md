---
author: ['Rob Cowie', 'Steve-V', 'sebastientinel']
date: 1649761835
title: "zoxide, TLDR Pages"
description: "zoxide, Keep track of the most frequently used directories."
categories: "common"
---
> Uses a ranking algorithm to navigate to the best match.

> More information: <https://github.com/ajeetdsouza/zoxide>.

- Go to the highest-ranked directory that contains "foo" in the name:

```bash
zoxide query foo
```

- Go to the highest-ranked directory that contains "foo" and then "bar":

```bash
zoxide query foo bar
```

- Start an interactive directory search (requires `fzf`):

```bash
zoxide query --interactive
```

- Add a directory or increment its rank:

```bash
zoxide add path/to/directory
```

- Remove a directory from `zoxide`'s database interactively:

```bash
zoxide remove path/to/directory --interactive
```

- Generate shell configuration for command aliases (`z`, `za`, `zi`, `zq`, `zr`):

```bash
zoxide init bash|fish|zsh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Steve-V](mailto:Steven.D.Vaught@gmail.com) | zoxide: add --interactive to remove example (#7977) | 2022-04-12T13:10:35 | [3f7ce811f7e2](https://github.com/tldr-pages/tldr/commit/3f7ce811f7e232da0f06d555c92c3d829c254154)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Rob Cowie](mailto:rob_cowie@mac.com) | zoxide: add page (#3925) | 2020-03-24T02:32:23 | [8367cbac3cc3](https://github.com/tldr-pages/tldr/commit/8367cbac3cc32cd0b46bcb71e11f5486ad1d5efb)

