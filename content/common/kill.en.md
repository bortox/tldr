---
author: ['Waldir Pimenta', 'Srinivasan R', 'Marco Bonelli', 'Ruben Vereecken', 'David Hatch', 'lincc', 'rprieto']
date: 1632006650
title: "kill, TLDR Pages"
description: "kill, Sends a signal to a process, usually related to stopping the process."
categories: "common"
---
> All signals except for SIGKILL and SIGSTOP can be intercepted by the process to perform a clean exit.

> More information: <https://manned.org/kill>.

- Terminate a program using the default SIGTERM (terminate) signal:

```bash
kill process_id
```

- List available signal names (to be used without the `SIG` prefix):

```bash
kill -l
```

- Terminate a background job:

```bash
kill %job_id
```

- Terminate a program using the SIGHUP (hang up) signal. Many daemons will reload instead of terminating:

```bash
kill -1|HUP process_id
```

- Terminate a program using the SIGINT (interrupt) signal. This is typically initiated by the user pressing `Ctrl + C`:

```bash
kill -2|INT process_id
```

- Signal the operating system to immediately terminate a program (which gets no chance to capture the signal):

```bash
kill -9|KILL process_id
```

- Signal the operating system to pause a program until a SIGCONT ("continue") signal is received:

```bash
kill -17|STOP process_id
```

- Send a `SIGUSR1` signal to all processes with the given GID (group id):

```bash
kill -SIGUSR1 -group_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | jobs, jstack, kill, killall: add more information link (#6545) | 2021-09-19T01:10:50 | [0e7393b78f1d](https://github.com/tldr-pages/tldr/commit/0e7393b78f1db36b5dfb377b3062c6b551a69e58)
[David Hatch](mailto:3mail48@gmail.com) | kill: adds a new example of killing a job (#3275) | 2019-09-22T06:13:07 | [c8ee465c2f59](https://github.com/tldr-pages/tldr/commit/c8ee465c2f596558ef61e3d82b69826b36a5fc1b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | brctl: add page. | 2019-01-11T01:53:19 | [ac5cd6d896a4](https://github.com/tldr-pages/tldr/commit/ac5cd6d896a449f8ea6144c932d610781e373877)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | kill: add two examples for signaling multiple processes | 2019-01-11T01:53:19 | [a4ade5e1a377](https://github.com/tldr-pages/tldr/commit/a4ade5e1a3778682ae268f589cbb1a3e720f39bd)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | kill: fix typo in example #6 description. | 2019-01-11T01:53:19 | [603f06d5015e](https://github.com/tldr-pages/tldr/commit/603f06d5015ee5bb59ca2680cfa717ee90144d9c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | kill.md: change signal explanation (closes #616) (#998) * add kill signal * 修改kill相关信号的注释 * kill.md: improve descriptions and [...] | 2016-08-21T15:36:24 | [e3553ac6f82f](https://github.com/tldr-pages/tldr/commit/e3553ac6f82fa106cf1a394a5a613948efb968be)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

