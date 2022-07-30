---
author: ['Brian Choromanski', 'Katy Moe', 'Axel Navarro', 'Alex Meng', 'Ruben Vereecken']
date: 1634764012
title: "pkill"
description: "pkill, Signal process by name."
categories: "common"
---
> Mostly used for stopping processes.

> More information: <https://www.man7.org/linux/man-pages/man1/pkill.1.html>.

- Kill all processes which match:

```bash
pkill "process_name"
```

- Kill all processes which match their full command instead of just the process name:

```bash
pkill -f "command_name"
```

- Force kill matching processes (can't be blocked):

```bash
pkill -9 "process_name"
```

- Send SIGUSR1 signal to processes which match:

```bash
pkill -USR1 "process_name"
```

- Kill the main `firefox` process to close the browser:

```bash
pkill --oldest "firefox"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Brian Choromanski](mailto:BrianChoromanski@gmail.com) | pkill: enhance -9 argument explanation (#7036) | 2021-10-20T23:06:52 | [356e95ce7954](https://github.com/tldr-pages/tldr/commit/356e95ce7954d5845edfab4e461466329503f066)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pkill: add --oldest example and link (#5445) | 2021-03-25T01:01:07 | [07c2ebcc511f](https://github.com/tldr-pages/tldr/commit/07c2ebcc511f2549ec267f9f3ef61b797ddb669d)
[Alex Meng](mailto:alexbmeng@gmail.com) | pkill: Add example with -f flag Its useful to be able to kill processes by their full command. The pgrep tldr page already has a -f [...] | 2016-01-13T23:03:35 | [017642dd9eab](https://github.com/tldr-pages/tldr/commit/017642dd9eab396f4505290597664630416c6e4d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Katy Moe](mailto:katy@katy.moe) | pkill: add page | 2016-01-02T01:48:55 | [652933225fca](https://github.com/tldr-pages/tldr/commit/652933225fca218ec724acd33e2b1d822462590f)

