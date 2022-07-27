---
author: ['Stig124', 'Russ Edwards']
date: 1625841955
title: "firejail, TLDR Pages"
description: "firejail, Securely sandboxes processes to containers using built-in Linux capabilities."
categories: "linux"
---
> More information: <https://manned.org/firejail>.

- Integrate firejail with your desktop environment:

```bash
sudo firecfg
```

- Open a restricted Mozilla Firefox:

```bash
firejail firefox
```

- Start a restricted Apache server on a known interface and address:

```bash
firejail --net=eth0 --ip=192.168.1.244 /etc/init.d/apache2 start
```

- List running sandboxes:

```bash
firejail --list
```

- List network activity from running sandboxes:

```bash
firejail --netstats
```

- Shutdown a running sandbox:

```bash
firejail --shutdown=7777
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Russ Edwards](mailto:redwards@digitellinc.com) | firejail: add page (#2354) | 2018-09-27T08:18:54 | [98f409a596e7](https://github.com/tldr-pages/tldr/commit/98f409a596e75fbc1e605c510238c3ed3c18df46)

