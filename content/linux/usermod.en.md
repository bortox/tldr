---
author: ['Patrice Denis', 'sebastientinel', 'Emily Grace Seville', 'Ruben Vereecken', 'Katy Moe']
date: 1643317713
title: "usermod, TLDR Pages"
description: "usermod, Modifies a user account."
categories: "linux"
---
> See also: `users`, `useradd`, `userdel`.

> More information: <https://manned.org/usermod>.

- Change a username:

```bash
sudo usermod --login new_username username
```

- Change a user id:

```bash
sudo usermod --uid id username
```

- Change a user shell:

```bash
sudo usermod --shell path/to/shell username
```

- Add a user to supplementary groups (mind the lack of whitespace):

```bash
sudo usermod --append --groups group1,group2,... username
```

- Change a user home directory:

```bash
sudo usermod --move-home --home path/to/new_home username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | useradd, userdel, usedmod, users: refresh page (#7661) | 2022-01-27T22:08:33 | [684f7bbc6577](https://github.com/tldr-pages/tldr/commit/684f7bbc65774c34ef7d57badefd75e2159dd943)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Katy Moe](mailto:katy@katy.moe) | useradd, userdel, usermod: move from common to linux directory | 2016-01-02T19:20:58 | [481a1d9bc968](https://github.com/tldr-pages/tldr/commit/481a1d9bc9680ed91b4e247e85f60e2792074e70)

