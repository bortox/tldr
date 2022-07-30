---
author: ['Fernando Alexandre', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "molecule"
description: "molecule, Molecule helps testing Ansible roles."
categories: "common"
---
> More information: <https://molecule.readthedocs.io>.

- Create a new Ansible role:

```bash
molecule init role --role-name role_name
```

- Run tests:

```bash
molecule test
```

- Start the instance:

```bash
molecule create
```

- Configure the instance:

```bash
molecule converge
```

- Log in into the instance:

```bash
molecule login
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Fernando Alexandre](mailto:jfernandoalex@gmail.com) | molecule: add page (#3223) | 2019-08-04T09:54:07 | [a9499b442f49](https://github.com/tldr-pages/tldr/commit/a9499b442f494774da2bcbf99154fba8a8420bd6)

