---
author: ['Waldir Pimenta', 'Marco Bonelli', 'Ruben Vereecken', 'Azrael JD', 'Igor Shubovych', 'Dylan Rees', 'Peter Tripp']
date: 1643125837
title: "su, TLDR Pages"
description: "su, Switch shell to another user."
categories: "common"
---
> More information: <https://manned.org/su>.

- Switch to superuser (requires the root password):

```bash
su
```

- Switch to a given user (requires the user's password):

```bash
su username
```

- Switch to a given user and simulate a full login shell:

```bash
su - username
```

- Execute a command as another user:

```bash
su - username -c "command"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | su: add more information link (#7705) | 2022-01-25T16:50:37 | [5b28d44739a4](https://github.com/tldr-pages/tldr/commit/5b28d44739a43a6e8ff073ce6de1ecc89d8dd7b3)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | su: reword example descriptions and add a new one (#3715) | 2019-12-30T18:30:30 | [cc6f7005c209](https://github.com/tldr-pages/tldr/commit/cc6f7005c209f8a5bdfe97ff19025ba1629ab997)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | su: reorder examples, simpler first. (#2732) | 2019-01-26T20:33:57 | [e921d0e6b67b](https://github.com/tldr-pages/tldr/commit/e921d0e6b67bcff771842210c404fc2ef744cc1b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed damage done by formatter some time ago | 2016-01-28T12:41:42 | [b4304e105004](https://github.com/tldr-pages/tldr/commit/b4304e1050045b410af4ac90f71a90aeb506de44)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge pull request #637 from notpeter/master Add su - for login shells | 2016-01-08T22:09:19 | [eb67b4948b91](https://github.com/tldr-pages/tldr/commit/eb67b4948b9197f1598eeb7ff3387c7eca7b79af)
[Peter Tripp](mailto:petertripp@gmail.com) | Add 'su -'. Apparently su -l is Linux/BSD only (no solaris) while su - is universal. | 2016-01-08T17:49:03 | [351145a3accd](https://github.com/tldr-pages/tldr/commit/351145a3accddf47a4eb7848d311f62d15f6d0ae)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create su.md | 2016-01-04T03:17:33 | [f3c40e2fe03f](https://github.com/tldr-pages/tldr/commit/f3c40e2fe03fea924a766f1731a801a9d4239841)

