---
author: ['kalebo', 'Igor Shubovych', 'Lucas Gabriel Schneider', 'Cvetomird91', 'Balázs Úr', 'Ruben Vereecken', 'Seth Falco', 'lincc']
date: 1632422063
title: "last"
description: "last, View the last logged in users."
categories: "common"
---
> More information: <https://manned.org/last>.

- View last logins, their duration and other information as read from `/var/log/wtmp`:

```bash
last
```

- Specify how many of the last logins to show:

```bash
last -n login_count
```

- Print the full date and time for entries and then display the hostname column last to prevent truncation:

```bash
last -F -a
```

- View all logins by a specific user and show the IP address instead of the hostname:

```bash
last username -i
```

- View all recorded reboots (i.e., the last logins of the pseudo user "reboot"):

```bash
last reboot
```

- View all recorded shutdowns (i.e., the last logins of the pseudo user "shutdown"):

```bash
last shutdown
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[kalebo](mailto:kaleb.olson@gmail.com) | last: add example that avoids hostname truncation (#1540) | 2017-10-17T08:30:41 | [fb91a188bda9](https://github.com/tldr-pages/tldr/commit/fb91a188bda926f0e34740a0d76608cad0aaaf7a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting | 2016-01-02T02:09:44 | [e45b0d719831](https://github.com/tldr-pages/tldr/commit/e45b0d7198312bd0acf9063244c185399a0ce457)
[Cvetomird91](mailto:cvetomirdenchev@gmail.com) | last: edited to stick to the convetion and added more options | 2015-12-31T16:21:42 | [fc835b18bbe7](https://github.com/tldr-pages/tldr/commit/fc835b18bbe7e0e2741d190d5f17f055f3d7cb78)

