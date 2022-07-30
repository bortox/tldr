---
author: ['Waldir Pimenta', 'slash3b', 'Zlatan Vasović', 'Alexandre Bruyant', 'bl-ue', 'Seth Falco']
date: 1629050349
title: "at"
description: "at, Executes commands at a specified time."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/at.1>.

- Open an `at` prompt to create a new set of scheduled commands, press `Ctrl + D` to save and exit:

```bash
at hh:mm
```

- Execute the commands and email the result using a local mailing program such as Sendmail:

```bash
at hh:mm -m
```

- Execute a script at the given time:

```bash
at hh:mm -f path/to/file
```

- Display a system notification at 11pm on February 18th:

```bash
echo "notify-send 'Wake up!'" | at 11pm Feb 18
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Alexandre Bruyant](mailto:alexandre.bruyant@gmail.com) | at: Update time format - fixes #4192 (#4202) | 2020-07-17T18:59:21 | [fc506737f1e7](https://github.com/tldr-pages/tldr/commit/fc506737f1e7e1acd969c530d01c67568bbbd420)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | at: add notify-send example (#4000) | 2020-05-03T14:12:22 | [8c7b7c95aab2](https://github.com/tldr-pages/tldr/commit/8c7b7c95aab22539419dd68d251b62f5704a8d7a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[slash3b](mailto:slash3b@gmail.com) | at: add page | 2016-06-30T18:49:25 | [3af52d7e19d7](https://github.com/tldr-pages/tldr/commit/3af52d7e19d78c2d8487dced83b4820f0688cd06)

