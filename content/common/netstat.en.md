---
author: ['marchersimon']
date: 1631999108
title: "netstat, TLDR Pages"
description: "netstat, Displays network-related information such as open connections, open socket ports, etc."
categories: "common"
---
> More information: <https://man7.org/linux/man-pages/man8/netstat.8.html>.

- List all ports:

```bash
netstat --all
```

- List all listening ports:

```bash
netstat --listening
```

- List listening TCP ports:

```bash
netstat --tcp
```

- Display PID and program names:

```bash
netstat --program
```

- List information continuously:

```bash
netstat --continuous
```

- List routes and do not resolve IP addresses to hostnames:

```bash
netstat --route --numeric
```

- List listening TCP and UDP ports (+ user and process if you're root):

```bash
netstat --listening --program --numeric --tcp --udp --extend
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

