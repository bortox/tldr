---
author: ['Yoshinari Takaoka', 'Waldir Pimenta', 'Vincent Bel', 'zlbabe', 'Jakub Kubryński', 'rprieto', "Ziyan 'Jerry' Chen", 'Ruben Vereecken', 'Futtetennista', 'lincc']
date: 1636580745
title: "lsof"
description: "lsof, Lists open files and the corresponding processes."
categories: "common"
---
> Note: Root privileges (or sudo) is required to list files opened by others.

> More information: <https://manned.org/lsof>.

- Find the processes that have a given file open:

```bash
lsof path/to/file
```

- Find the process that opened a local internet port:

```bash
lsof -i :port
```

- Only output the process ID (PID):

```bash
lsof -t path/to/file
```

- List files opened by the given user:

```bash
lsof -u username
```

- List files opened by the given command or process:

```bash
lsof -c process_or_command_name
```

- List files opened by a specific process, given its PID:

```bash
lsof -p PID
```

- List open files in a directory:

```bash
lsof +D path/to/directory
```

- Find the process that is listening on a local IPv6 TCP port and don't convert network or port numbers:

```bash
lsof -i6TCP:port -sTCP:LISTEN -n -P
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ziyan 'Jerry' Chen](mailto:jerryc443@gmail.com) | lsof: edit -iTCP example with -i6TCP, -n and -P (#7153) | 2021-11-10T22:45:45 | [1eb7603197d9](https://github.com/tldr-pages/tldr/commit/1eb7603197d97277d81a1313aefb51ec17a73c32)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Futtetennista](mailto:futtetennista@pm.me) | lsof: find the process listening on a local port (#3188) | 2019-08-20T20:13:45 | [5532175b1571](https://github.com/tldr-pages/tldr/commit/5532175b15718906d8823e8a4984be3abdbaaabb)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | lsof: list opened files in a directory (#1449) | 2017-08-17T14:08:23 | [d86e7e35a2fd](https://github.com/tldr-pages/tldr/commit/d86e7e35a2fd15014ae36f053ae880f1cc813f9f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | lsof: shorten main desc, expand PID acronym (#1346) | 2017-04-22T20:44:03 | [69c12013b336](https://github.com/tldr-pages/tldr/commit/69c12013b3360e490a152b8d39f2999eed983c39)
[Jakub Kubryński](mailto:jkubrynski@gmail.com) | Add description how to use lsof by PID | 2017-03-01T16:43:17 | [b937aa13a893](https://github.com/tldr-pages/tldr/commit/b937aa13a893776d64b4f8aa661ead4d3925de30)
[Vincent Bel](mailto:buaazqh@gmail.com) | [lsof] Fixed typo after reformatted The last letter of last word of [the three lines](https://github.com/tldr- [...] | 2016-01-28T07:35:41 | [72548b6443c0](https://github.com/tldr-pages/tldr/commit/72548b6443c042c1da74691f78827d180d5b9924)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | Merge branch 'master' into lsof_add_some_options_example | 2016-01-10T13:37:46 | [dc911022058f](https://github.com/tldr-pages/tldr/commit/dc911022058f291aeb70ec2e127d5d21abc44c6b)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | - deleted unnecessary descriptions. | 2016-01-10T13:33:09 | [b8d24b5f74b3](https://github.com/tldr-pages/tldr/commit/b8d24b5f74b3b9400ae4fd90fb76345c1f84bc32)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | fixed poor english :( | 2016-01-05T22:29:14 | [7a01d25b6f5a](https://github.com/tldr-pages/tldr/commit/7a01d25b6f5a943ce5e48d8dad4b1d37bae21a30)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | removed kill -9 pipe. | 2016-01-05T22:26:36 | [28f29660c33d](https://github.com/tldr-pages/tldr/commit/28f29660c33d2f3ed5b805fe882b50777733e00d)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | replaced {{8080}} with {{port}} to follow format conventions. | 2016-01-05T22:24:23 | [7d7a50568ffd](https://github.com/tldr-pages/tldr/commit/7d7a50568ffddb7a4072aff6627dc685efec6ea1)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | lsof: add -u, -c example and note about privileges | 2016-01-03T19:47:24 | [b10743579347](https://github.com/tldr-pages/tldr/commit/b107435793478595a99ff1654024b9e8fae56422)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

