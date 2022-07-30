---
author: ['sedrubal', 'Lucas Gabriel Schneider', 'lbonanomi', 'marchersimon']
date: 1618756407
title: "command"
description: "command, Command forces the shell to execute the program and ignore any functions, builtins and aliases with the same name."
categories: "common"
---
> More information: <https://manned.org/command>.

- Execute the `ls` program literally, even if an `ls` alias exists:

```bash
command ls
```

- Display the path to the executable or the alias definition of a specific command:

```bash
command -v command_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | command: add link | 2021-04-18T16:33:27 | [e7add447e9df](https://github.com/tldr-pages/tldr/commit/e7add447e9df5fcf3ff8f58322df99fdcbee5ce5)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[sedrubal](mailto:sedrubal@users.noreply.github.com) | command: add -v example (#4762) | 2020-10-24T14:12:39 | [5fd5e9bba2c6](https://github.com/tldr-pages/tldr/commit/5fd5e9bba2c652acf20252e3572d2e075c6c8658)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | command: move to common/ | 2019-05-23T18:15:31 | [6b34c5ce3165](https://github.com/tldr-pages/tldr/commit/6b34c5ce31657f4081f1452c239016df5669216d)

