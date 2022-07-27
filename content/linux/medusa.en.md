---
author: ['UnleashTheCode', 'Lucas Gabriel Schneider', 'Seth Falco', 'bl-ue']
date: 1629110041
title: "Medusa, TLDR Pages"
description: "Medusa, A modular and parallel login brute-forcer for a variety of protocols."
categories: "linux"
---
> More information: <https://manned.org/medusa>.

- Execute brute force against an FTP server using a file containing usernames and a file containing passwords:

```bash
medusa -M ftp -h host -U path/to/username_file -P path/to/password_file
```

- Execute a login attempt against an HTTP server using the username, password and user-agent specified:

```bash
medusa -M HTTP -h host -u username -p password -m USER-AGENT:"Agent"
```

- Execute a brute force against a MySQL server using a file containing usernames and a hash:

```bash
medusa -M mysql -h host -U path/to/username_file -p hash -m PASS:HASH
```

- Execute a brute force against a list of SMB servers using a username and a pwdump file:

```bash
medusa -M smbnt -H path/to/hosts_file -C path/to/pwdump_file -u username -m PASS:HASH
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[UnleashTheCode](mailto:danteodorandrei@outlook.com) | medusa: add page (#3899) | 2020-03-10T15:26:16 | [6dd193dda803](https://github.com/tldr-pages/tldr/commit/6dd193dda803a0a6f2053ba5ae6dbd7ab06d1fec)

