---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'rprieto', 'lord63', 'bl-ue', 'Ivan Aracki', 'Ruben Vereecken']
date: 1642512520
title: "alias"
description: "alias, Creates aliases -- words that are replaced by a command string."
categories: "common"
---
> Aliases expire with the current shell session unless defined in the shell's configuration file, e.g. `~/.bashrc`.

> More information: <https://tldp.org/LDP/abs/html/aliases.html>.

- List all aliases:

```bash
alias
```

- Create a generic alias:

```bash
alias word="command"
```

- View the command associated to a given alias:

```bash
alias word
```

- Remove an aliased command:

```bash
unalias word
```

- Turn `rm` into an interactive command:

```bash
alias rm="rm --interactive"
```

- Create `la` as a shortcut for `ls --all`:

```bash
alias la="ls --all"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | Use long options (#7675) | 2022-01-18T14:28:40 | [d98e164b69a6](https://github.com/tldr-pages/tldr/commit/d98e164b69a6ecb75e97a05201e2d18d9aec1e16)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | alias: add list all aliases (#3019) | 2019-05-15T01:05:57 | [5e876b3a9db2](https://github.com/tldr-pages/tldr/commit/5e876b3a9db2279a6d6462d10eb888eaf085514b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | alias: wrap rm command in backticks (#2888) * alias (pt-BR): wrap rm command in backticks * alias: wrap rm command in backticks | 2019-04-11T00:39:39 | [939a446a683e](https://github.com/tldr-pages/tldr/commit/939a446a683e67944a38a4dda2c507cd9c38f9a6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | alias: change main description; add view example (#1224) | 2017-01-04T22:52:02 | [07c2de5e584b](https://github.com/tldr-pages/tldr/commit/07c2de5e584bd617c6097cbf4d4b84af4ab5054d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | alias: various tweaks (#1135) - add a caveat to the main description about an aliases not being permanently saved - tweak the [...] | 2016-10-29T17:03:11 | [b5f522803a26](https://github.com/tldr-pages/tldr/commit/b5f522803a2605f9a8fc85805848454c505ac756)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

