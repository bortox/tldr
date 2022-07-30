---
author: ['Waldir Pimenta', 'Igor Shubovych', 'Agniva De Sarker', 'Ein Verne', 'Lucas Gabriel Schneider', 'mihainsto', 'CleanMachine1', 'Ruben Vereecken']
date: 1624920504
title: "top"
description: "top, Display dynamic real-time information about running processes."
categories: "linux"
---
> More information: <https://manned.org/top>.

- Start top:

```bash
top
```

- Do not show any idle or zombie processes:

```bash
top -i
```

- Show only processes owned by given user:

```bash
top -u username
```

- Sort processes by a field:

```bash
top -o field_name
```

- Show the individual threads of a given process:

```bash
top -Hp process_id
```

- Show only the processes with the given PID(s), passed as a comma-separated list. (Normally you wouldn't know PIDs off hand. This example picks the PIDs from the process name):

```bash
top -p $(pgrep -d ',' process_name)
```

- Get help about interactive commands:

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/t*: add information link (#6166) | 2021-06-29T00:48:24 | [d86d3d6206bd](https://github.com/tldr-pages/tldr/commit/d86d3d6206bdf76257ce480be4a8a71d2d4fdda6)
[mihainsto](mailto:44275480+mihainsto@users.noreply.github.com) | top: add sorting option (#4135) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-06-29T21:09:16 | [b697be87f3fd](https://github.com/tldr-pages/tldr/commit/b697be87f3fdeda1a5f95307cae08514118735b0)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Ein Verne](mailto:einverne@gmail.com) | top: update page (#3744) * top: update page * Update pages/linux/top.md Co-Authored-By: Zlatan Vasović <zlatanvasovic@gmail.com> Co- [...] | 2020-01-11T14:53:58 | [39fd1720c24e](https://github.com/tldr-pages/tldr/commit/39fd1720c24e122000484b2eb174d01603154771)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | top.md: various tweaks (#923) - standardize examples to use generic tokens - format tokens using snake_case - use "show" for all [...] | 2016-06-22T20:02:12 | [3c56b7b342c2](https://github.com/tldr-pages/tldr/commit/3c56b7b342c2345082d1fcb39cb0b9bbf9d7556e)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | top: Add a better example (#921) | 2016-06-22T13:05:00 | [f022954edafe](https://github.com/tldr-pages/tldr/commit/f022954edafee22a1389d46c62113e23284829d7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | top: removing batch mode examples, because it is not obvious | 2015-12-09T18:19:27 | [8bf010111a68](https://github.com/tldr-pages/tldr/commit/8bf010111a680c3298b7e1350a71addd5cd90b5a)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Added top command for Linux and OSX | 2015-12-09T18:19:27 | [63472222b831](https://github.com/tldr-pages/tldr/commit/63472222b8311001bf1b8ee3dbb623efa2df6bef)

