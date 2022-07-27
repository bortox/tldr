---
author: ['marchersimon', 'Starbeamrainbowlabs']
date: 1618869951
title: "dirs, TLDR Pages"
description: "dirs, Displays or manipulates the directory stack."
categories: "common"
---
> The directory stack is a list of recently visited directories that can be manipulated with the `pushd` and `popd` commands.

> More information: <https://www.gnu.org/software/bash/manual/bash.html#Directory-Stack-Builtins>.

- Display the directory stack with a space between each entry:

```bash
dirs
```

- Display the directory stack with one entry per line:

```bash
dirs -p
```

- Display only the nth entry in the directory stack, starting at 0:

```bash
dirs +N
```

- Clear the directory stack:

```bash
dirs -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirs: edit link Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-20T00:05:51 | [5d2fa2261db4](https://github.com/tldr-pages/tldr/commit/5d2fa2261db4d26e09c26f72f35d52e35dcf1bec)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Added the dirs command Fix build & Add definition of stack Added reference to pushd/popd in description | 2016-02-10T21:20:54 | [a76141742fb5](https://github.com/tldr-pages/tldr/commit/a76141742fb5089f0bf4e4581a39e5a53786605e)

