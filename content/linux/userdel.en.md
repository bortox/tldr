---
author: ['Mateusz Soszyński', 'Patrice Denis', 'lord63', 'Emily Grace Seville', 'Ruben Vereecken', 'Katy Moe']
date: 1643317713
title: "userdel, TLDR Pages"
description: "userdel, Remove a user account or remove a user from a group."
categories: "linux"
---
> See also: `users`, `useradd`, `usermod`.

> More information: <https://manned.org/userdel>.

- Remove a user:

```bash
sudo userdel username
```

- Remove a user in other root directory:

```bash
sudo userdel --root path/to/other/root username
```

- Remove a user along with the home directory and mail spool:

```bash
sudo userdel --remove username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | useradd, userdel, usedmod, users: refresh page (#7661) | 2022-01-27T22:08:33 | [684f7bbc6577](https://github.com/tldr-pages/tldr/commit/684f7bbc65774c34ef7d57badefd75e2159dd943)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | deluser, userdel: add page (#5245) | 2021-02-07T20:05:03 | [7dcdcea28c3c](https://github.com/tldr-pages/tldr/commit/7dcdcea28c3c47f411c9611ee1827f8dc83ad938)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Katy Moe](mailto:katy@katy.moe) | useradd, userdel, usermod: move from common to linux directory | 2016-01-02T19:20:58 | [481a1d9bc968](https://github.com/tldr-pages/tldr/commit/481a1d9bc9680ed91b4e247e85f60e2792074e70)
[lord63](mailto:lord63.j@gmail.com) | Remove userdel command page in linux folder that's because we've have it in common folder, and they are the same. | 2015-09-05T16:16:20 | [a52648f81116](https://github.com/tldr-pages/tldr/commit/a52648f81116f93cad8a7c353e1073b27eaac40c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Added userdel to linux | 2014-03-24T10:58:38 | [3e3a8a359c75](https://github.com/tldr-pages/tldr/commit/3e3a8a359c750857b9ab4974f8398de171a35496)

