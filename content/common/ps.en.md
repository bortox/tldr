---
author: ['Frank Dietrich', 'Ruben Vereecken', 'Martin Barth', 'zlbabe', 'Joshua Shanks', 'rprieto', 'Seth Falco']
date: 1633557112
title: "ps, TLDR Pages"
description: "ps, Information about running processes."
categories: "common"
---
> More information: <https://manned.org/ps>.

- List all running processes:

```bash
ps aux
```

- List all running processes including the full command string:

```bash
ps auxww
```

- Search for a process that matches a string:

```bash
ps aux | grep string
```

- List all processes of the current user in extra full format:

```bash
ps --user $(id -u) -F
```

- List all processes of the current user as a tree:

```bash
ps --user $(id -u) f
```

- Get the parent PID of a process:

```bash
ps -o ppid= -p pid
```

- Sort processes by memory consumption:

```bash
ps --sort size
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | ps, pv, pygmentize, quota, rabin2: add link (#6830) | 2021-10-06T23:51:52 | [52b9aaf74c57](https://github.com/tldr-pages/tldr/commit/52b9aaf74c571d0ee04b6f2986e09fff22ba7256)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Martin Barth](mailto:ufobat@users.noreply.github.com) | ps: added sort example (#4216) | 2020-07-28T16:34:12 | [8f694a13ea5c](https://github.com/tldr-pages/tldr/commit/8f694a13ea5c5f7cb18f3169d1603f7fb4c3554f)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | Update ps.md | 2018-01-15T22:51:45 | [4afea4ad1a7e](https://github.com/tldr-pages/tldr/commit/4afea4ad1a7ef22eb147b5349c84534af8e23728)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | ps: get the parent pid | 2018-01-15T22:36:37 | [602e8187a41d](https://github.com/tldr-pages/tldr/commit/602e8187a41de56cd0e7aa5a8206aad35042815d)
[Frank Dietrich](mailto:bits_n_bytes@gmx.de) | user short option for `id` command | 2017-11-24T13:04:02 | [9ec1c1f4a5ad](https://github.com/tldr-pages/tldr/commit/9ec1c1f4a5ad7bbb3348ef864fad857e4a8f4927)
[Frank Dietrich](mailto:bits_n_bytes@gmx.de) | amend based on the PR comments | 2017-11-24T12:50:38 | [ded5c11e43e9](https://github.com/tldr-pages/tldr/commit/ded5c11e43e961d2dd3e27e09a945b697d653085)
[Frank Dietrich](mailto:bits_n_bytes@gmx.de) | fix example description | 2017-11-23T13:01:50 | [9592b58954b5](https://github.com/tldr-pages/tldr/commit/9592b58954b51725224996bb640098520d7f38af)
[Frank Dietrich](mailto:bits_n_bytes@gmx.de) | add examples for current user processes #fixes 1610 | 2017-11-23T12:53:54 | [1cf9fda3ee26](https://github.com/tldr-pages/tldr/commit/1cf9fda3ee268ab50e3e2ec2a0e4d17b96414ba4)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Added a grep use case to ps | 2014-03-24T00:52:15 | [a6ae297b6a35](https://github.com/tldr-pages/tldr/commit/a6ae297b6a3535021b8db11185bcdde68fa366be)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

