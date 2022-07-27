---
author: ['lmazardo', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "lastcomm, TLDR Pages"
description: "lastcomm, Show last commands executed."
categories: "linux"
---
> More information: <https://manpages.debian.org/stable/acct/lastcomm.1.en.html>.

- Print information about all the commands in the acct (record file):

```bash
lastcomm
```

- Display commands executed by a given user:

```bash
lastcomm --user user
```

- Display information about a given command executed on the system:

```bash
lastcomm --command command
```

- Display information about commands executed on a given terminal:

```bash
lastcomm --tty terminal_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[lmazardo](mailto:luc@mazardo.com) | lastcomm: add new page (#3086) (#3333) | 2019-10-10T05:38:13 | [1041a29fdb64](https://github.com/tldr-pages/tldr/commit/1041a29fdb6445ba978f4832b1aac3a158d75b66)

