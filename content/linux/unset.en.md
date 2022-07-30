---
author: ['Ronnie Gane', 'jn64', 'CleanMachine1']
date: 1626023849
title: "unset"
description: "unset, Remove shell variables or functions."
categories: "linux"
---
> More information: <https://manned.org/unset>.

- Remove the variable `foo`, or if the variable doesn't exist, remove the function `foo`:

```bash
unset foo
```

- Remove the variables foo and bar:

```bash
unset -v foo bar
```

- Remove the function my_func:

```bash
unset -f my_func
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/u*: add links (#6190) | 2021-07-11T19:17:29 | [3ac60f1062ba](https://github.com/tldr-pages/tldr/commit/3ac60f1062ba714b493cee9c4e413901867c9f93)
[jn64](mailto:23169302+jn64@users.noreply.github.com) | unset: clarify example with no options (#4126) | 2020-07-05T22:50:40 | [222bc41873be](https://github.com/tldr-pages/tldr/commit/222bc41873be0a8c131ca420bc51ff79d313d620)
[Ronnie Gane](mailto:ronniegane@gmail.com) | unset: add page (#2570) | 2018-12-01T18:55:20 | [0ad8632483ad](https://github.com/tldr-pages/tldr/commit/0ad8632483ad54f82639ef9bbabcc08e28f57d28)

