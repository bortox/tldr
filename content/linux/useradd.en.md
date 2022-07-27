---
author: ['Patrice Denis', 'sebastientinel', 'Emily Grace Seville', 'Ruben Vereecken', 'Katy Moe', 'Starbeamrainbowlabs']
date: 1643317713
title: "useradd, TLDR Pages"
description: "useradd, Create a new user."
categories: "linux"
---
> See also: `users`, `userdel`, `usermod`.

> More information: <https://manned.org/useradd>.

- Create a new user:

```bash
sudo useradd username
```

- Create a new user with the specified user id:

```bash
sudo useradd --uid id username
```

- Create a new user with the specified shell:

```bash
sudo useradd --shell path/to/shell username
```

- Create a new user belonging to additional groups (mind the lack of whitespace):

```bash
sudo useradd --groups group1,group2,... username
```

- Create a new user with the default home directory:

```bash
sudo useradd --create-home username
```

- Create a new user with the home directory filled by template directory files:

```bash
sudo useradd --skel path/to/template_directory --create-home username
```

- Create a new system user without the home directory:

```bash
sudo useradd --system username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | useradd, userdel, usedmod, users: refresh page (#7661) | 2022-01-27T22:08:33 | [684f7bbc6577](https://github.com/tldr-pages/tldr/commit/684f7bbc65774c34ef7d57badefd75e2159dd943)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Converted all arguments to the long form | 2016-09-10T20:35:35 | [a9fea19ec4c1](https://github.com/tldr-pages/tldr/commit/a9fea19ec4c19595f227399a866a6e40fe31a97f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Reworded other example to aid simplicity. | 2016-09-10T20:34:16 | [b36b02692f66](https://github.com/tldr-pages/tldr/commit/b36b02692f66fb8a885886646b53319593c56ba1)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Add command to create a system user to useradd. Creating a new system user is common administrative task on the average linux server. [...] | 2016-09-10T11:45:36 | [49327963e207](https://github.com/tldr-pages/tldr/commit/49327963e20736bdd80df68888168137b351f714)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Katy Moe](mailto:katy@katy.moe) | useradd, userdel, usermod: move from common to linux directory | 2016-01-02T19:20:58 | [481a1d9bc968](https://github.com/tldr-pages/tldr/commit/481a1d9bc9680ed91b4e247e85f60e2792074e70)

