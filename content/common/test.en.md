---
author: ['Pierre Rudloff', 'Ruben Vereecken', 'Krzysztof Bociurko', 'Igor Shubovych', 'Dario Vladović']
date: 1636246663
title: "test, TLDR Pages"
description: "test, Check file types and compare values."
categories: "common"
---
> Returns 0 if the condition evaluates to true, 1 if it evaluates to false.

> More information: <https://www.gnu.org/software/coreutils/test>.

- Test if a given variable is equal to a given string:

```bash
test "$MY_VAR" == "/bin/zsh"
```

- Test if a given variable is empty:

```bash
test -z "$GIT_BRANCH"
```

- Test if a file exists:

```bash
test -f "path/to/file_or_directory"
```

- Test if a directory does not exist:

```bash
test ! -d "path/to/directory"
```

- If-else statement:

```bash
test condition && echo "true" || echo "false"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | [, test: add Polish translation (#7354) | 2021-11-07T01:57:43 | [78b19eebc367](https://github.com/tldr-pages/tldr/commit/78b19eebc3677a1ae9890450708fff2a89f77ffa)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Pierre Rudloff](mailto:contact@rudloff.pro) | test, [: add page, improve examples (#5205) | 2021-03-10T20:24:11 | [3f25e8f0a027](https://github.com/tldr-pages/tldr/commit/3f25e8f0a0271992fead048c51923bde16eb139a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | test: add page | 2015-12-12T23:08:54 | [893f4459b619](https://github.com/tldr-pages/tldr/commit/893f4459b619326f380bb8950a3457bb470db353)

