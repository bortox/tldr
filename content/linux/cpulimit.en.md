---
author: ['Starbeamrainbowlabs', 'Marco Bonelli']
date: 1562441623
title: "cpulimit"
description: "cpulimit, A tool to throttle the CPU usage of other processes."
categories: "linux"
---
> More information: <http://cpulimit.sourceforge.net/>.

- Limit an existing process with PID 1234 to only use 25% of the CPU:

```bash
cpulimit --pid 1234 --limit 25%
```

- Limit an existing program by its executable name:

```bash
cpulimit --exe program --limit 25
```

- Launch a given program and limit it to only use 50% of the CPU:

```bash
cpulimit --limit 50 -- program arg1 arg2 ...
```

- Launch a program, limit its CPU usage to 50% and run cpulimit in the background:

```bash
cpulimit --limit 50 --background -- program
```

- Kill its process if the program's CPU usage goes over 50%:

```bash
cpulimit --limit 50 --kill -- program
```

- Throttle both it and its child processes so that none go about 25% CPU:

```bash
cpulimit --limit 25 --monitor-forks -- program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | cpulimit: correct wrong examples. (#3171) | 2019-07-06T21:33:43 | [f36c745018fb](https://github.com/tldr-pages/tldr/commit/f36c745018fb777203b2804fffcf253a152bad17)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | cpulimit: add page (#3067) | 2019-06-02T15:27:24 | [e8882b55734e](https://github.com/tldr-pages/tldr/commit/e8882b55734e11774beb95eeb81bfd55fca761a2)

