---
author: ['Natechawin Suthison', 'Seth Falco']
date: 1629050349
title: "dockerd"
description: "dockerd, A persistent process to start and manage docker containers."
categories: "linux"
---
> More information: <https://docs.docker.com/engine/reference/commandline/dockerd/>.

- Run docker daemon:

```bash
dockerd
```

- Run docker daemon and config it to listen to specific sockets (UNIX and TCP):

```bash
dockerd --host unix://path/to/tmp.sock --host tcp://ip
```

- Run with specific daemon PID file:

```bash
dockerd --pidfile path/to/pid_file
```

- Run in debug mode:

```bash
dockerd --debug
```

- Run and set a specific log level:

```bash
dockerd --log-level=debug|info|warn|error|fatal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Natechawin Suthison](mailto:natechawin@gmail.com) | dockerd: add page (#3349) | 2019-10-15T06:34:31 | [448cb24fe058](https://github.com/tldr-pages/tldr/commit/448cb24fe0585ec438a890b97219558d946b1231)

