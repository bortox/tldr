---
author: ['Stig124', 'Lucas Gabriel Schneider', 'msdlisper']
date: 1625841955
title: "gpasswd"
description: "gpasswd, Administer `/etc/group` and `/etc/gshadow`."
categories: "linux"
---
> More information: <https://manned.org/gpasswd>.

- Define group administrators:

```bash
sudo gpasswd -A user1,user2 group
```

- Set the list of group members:

```bash
sudo gpasswd -M user1,user2 group
```

- Create a password for the named group:

```bash
gpasswd group
```

- Add a user to the named group:

```bash
gpasswd -a user group
```

- Remove a user from the named group:

```bash
gpasswd -d user group
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[msdlisper](mailto:whatabigbirl@gmail.com) | gpasswd: add page (#2480) | 2018-10-30T09:39:36 | [2fe3be3c92a5](https://github.com/tldr-pages/tldr/commit/2fe3be3c92a5a2fe248b4dec4cbcf07ceff9eb13)

