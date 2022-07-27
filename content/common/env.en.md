---
author: ['Srinivasan R', 'Donovan Mueller', 'Ruben Vereecken', 'litblaky', 'Chuancong Gao', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "env, TLDR Pages"
description: "env, Show the environment or run a program in a modified environment."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/env>.

- Show the environment:

```bash
env
```

- Run a program. Often used in scripts after the shebang (#!) for looking up the path to the program:

```bash
env program
```

- Clear the environment and run a program:

```bash
env -i program
```

- Remove variable from the environment and run a program:

```bash
env -u variable program
```

- Set a variable and run a program:

```bash
env variable=value program
```

- Set multiple variables and run a program:

```bash
env variable1=value variable2=value variable3=value program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | env: add more information link (#5607) | 2021-03-30T15:57:12 | [fed21f3974b4](https://github.com/tldr-pages/tldr/commit/fed21f3974b4d2efe402133ff8d94a04bcf981ce)
[Donovan Mueller](mailto:donut@users.noreply.github.com) | env: add multi var set example (#4331) | 2020-09-11T13:18:16 | [f145e33a335d](https://github.com/tldr-pages/tldr/commit/f145e33a335ddb30ed43dff27213d6121630509f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'env' of git://github.com/chuanconggao/tldr into chuanconggao-env Conflicts: pages/common/env.md | 2016-01-21T13:32:55 | [ea65d15a02ac](https://github.com/tldr-pages/tldr/commit/ea65d15a02ace1e6ee2b50826bc657872693e5c3)
[Chuancong Gao](mailto:chuanconggao@users.noreply.github.com) | env: update | 2016-01-11T16:21:16 | [d92791b28758](https://github.com/tldr-pages/tldr/commit/d92791b287588d71556900db813ae6b311f218df)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[litblaky](mailto:litblaky@gmail.com) | add env command | 2014-04-08T16:47:38 | [0aa39f0aa2ca](https://github.com/tldr-pages/tldr/commit/0aa39f0aa2cacac6f76277d4150fb8374f641faa)

