---
author: ['Axel Navarro', 'Dennis Weber', 'Seth Falco']
date: 1642131234
title: "faketime"
description: "faketime, Fake the system time for a given command."
categories: "linux"
---
> More information: <https://manned.org/faketime>.

- Fake the time to this evening, before printing the result of `date`:

```bash
faketime 'today 23:30' date
```

- Open a new `bash` shell, which uses yesterday as the current date:

```bash
faketime 'yesterday' bash
```

- Simulate how a program would act next Friday night:

```bash
faketime 'next Friday 1 am' path/to/program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dennis Weber](mailto:Nijin22@users.noreply.github.com) | faketime: add page (#3103) | 2019-06-12T16:52:24 | [fbf9b8bf3f19](https://github.com/tldr-pages/tldr/commit/fbf9b8bf3f19b126a95dea394fc21434efd07455)

