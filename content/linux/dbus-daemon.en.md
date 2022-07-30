---
author: ['Waldir Pimenta', 'Stig124', 'Owen Voke', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "dbus-daemon"
description: "dbus-daemon, The D-Bus message daemon, allowing multiple programs to exchange messages."
categories: "linux"
---
> More information: <https://www.freedesktop.org/wiki/Software/dbus/>.

- Run the daemon with a configuration file:

```bash
dbus-daemon --config-file path/to/file
```

- Run the daemon with the standard per-login-session message bus configuration:

```bash
dbus-daemon --session
```

- Run the daemon with the standard systemwide message bus configuration:

```bash
dbus-daemon --system
```

- Set the address to listen on and override the configuration value for it:

```bash
dbus-daemon --address address
```

- Output the process ID to stdout:

```bash
dbus-daemon --print-pid
```

- Force the message bus to write to the system log for messages:

```bash
dbus-daemon --syslog
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Owen Voke](mailto:owzie123@gmail.com) | dbus-daemon: add page (#2072) | 2018-04-17T21:38:17 | [a47a8a88d312](https://github.com/tldr-pages/tldr/commit/a47a8a88d312ac89896fcb445c28853b99e43ad4)

