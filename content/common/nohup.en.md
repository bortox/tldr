---
author: ['Dario Vladović', 'Antoine Amara', 'Srinivasan R', 'Guido Lena Cota', 'Ruben Vereecken', 'Seth Falco', 'marchersimon']
date: 1634641602
title: "nohup"
description: "nohup, Allows for a process to live when the terminal gets killed."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/nohup>.

- Run a process that can live beyond the terminal:

```bash
nohup command command_arguments
```

- Launch nohup in background mode:

```bash
nohup command command_arguments &
```

- Run a shell script that can live beyond the terminal:

```bash
nohup path/to/script.sh &
```

- Run a process and write the output to a specific file:

```bash
nohup command command_arguments > path/to/output_file &
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Amara](mailto:amara.antoine@gmail.com) | nohup: add background and output to file examples (#7085) | 2021-10-19T13:06:42 | [af038c76b26c](https://github.com/tldr-pages/tldr/commit/af038c76b26ccf54844c681563b0006af0ec9a59)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nohup: add link (#5617) | 2021-03-30T16:01:11 | [277fb1112311](https://github.com/tldr-pages/tldr/commit/277fb1112311d4c46c26d4f74e70ea5a7cb87173)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Added nohup page | 2014-03-24T11:17:15 | [0e60666be295](https://github.com/tldr-pages/tldr/commit/0e60666be295a2fe5978539c65613143eb974bfb)

