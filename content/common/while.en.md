---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'git-em', 'Denis Sokolov', 'Lucas Gabriel Schneider']
date: 1646140877
title: "while, TLDR Pages"
description: "while, Simple shell loop."
categories: "common"
---
> More information: <https://manned.org/while>.

- Read stdin and perform an action on every line:

```bash
while read line; do echo "$line"; done
```

- Execute a command forever once every second:

```bash
while :; do command; sleep 1; done
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | brightness, n, open, pbcopy, pbpaste, rename, route, rubocop, softwareupdate, timed, where, while, xed, xip: add link (#7831) | 2022-03-01T14:21:17 | [2ce63b334ebd](https://github.com/tldr-pages/tldr/commit/2ce63b334ebd26bb9e46be904fcc19884974e397)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Denis Sokolov](mailto:denis@sokolov.cc) | for/if/while: add | 2016-01-07T16:40:49 | [27cc01819f77](https://github.com/tldr-pages/tldr/commit/27cc01819f7703b54ddf368990b96ea105d1e18a)

