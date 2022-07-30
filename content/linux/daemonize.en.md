---
author: ['Alistair Young', 'Seth Falco']
date: 1629050349
title: "daemonize"
description: "daemonize, Run a command (that does not daemonize itself) as a Unix daemon."
categories: "linux"
---
> More information: <http://software.clapper.org/daemonize/>.

- Run a command as a daemon:

```bash
daemonize command command_arguments
```

- Write the PID to the specified file:

```bash
daemonize -p path/to/pidfile command command_arguments
```

- Use a lock file to ensure that only one instance runs at a time:

```bash
daemonize -l path/to/lockfile command command_arguments
```

- Use the specified user account:

```bash
sudo daemonize -u user command command_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Alistair Young](mailto:avatar@arkane-systems.net) | daemonize: add page (#3228) | 2019-08-07T19:25:50 | [6979688bcaf2](https://github.com/tldr-pages/tldr/commit/6979688bcaf2c670e171ce11df04e7b5ed6ff2c2)

