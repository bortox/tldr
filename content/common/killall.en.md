---
author: ['Jade Thornton', 'Waldir Pimenta', 'lincc']
date: 1632006650
title: "killall"
description: "killall, Send kill signal to all instances of a process by name (must be exact name)."
categories: "common"
---
> All signals except SIGKILL and SIGSTOP can be intercepted by the process, allowing a clean exit.

> More information: <https://manned.org/killall>.

- Terminate a process using the default SIGTERM (terminate) signal:

```bash
killall process_name
```

- List available signal names (to be used without the 'SIG' prefix):

```bash
killall --list
```

- Interactively ask for confirmation before termination:

```bash
killall -i process_name
```

- Terminate a process using the SIGINT (interrupt) signal, which is the same signal sent by pressing `Ctrl + C`:

```bash
killall -INT process_name
```

- Force kill a process:

```bash
killall -KILL process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | jobs, jstack, kill, killall: add more information link (#6545) | 2021-09-19T01:10:50 | [0e7393b78f1d](https://github.com/tldr-pages/tldr/commit/0e7393b78f1db36b5dfb377b3062c6b551a69e58)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Jade Thornton](mailto:jade@jmthornton.net) | killall: add page (#1317) | 2017-04-09T18:41:36 | [8dbc49c36b03](https://github.com/tldr-pages/tldr/commit/8dbc49c36b03298455b9fc39b637e084a1338a47)

