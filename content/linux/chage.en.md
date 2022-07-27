---
author: ['slash3b', 'Stig124', 'Ilya Tribusean', 'Lucas Gabriel Schneider', 'Axel Navarro']
date: 1632142761
title: "chage, TLDR Pages"
description: "chage, Change user account and password expiry information."
categories: "linux"
---
> More information: <https://manned.org/chage>.

- List password information for the user:

```bash
chage --list username
```

- Enable password expiration in 10 days:

```bash
sudo chage --maxdays 10 username
```

- Disable password expiration:

```bash
sudo chage --maxdays -1 username
```

- Set account expiration date:

```bash
sudo chage --expiredate YYYY-MM-DD username
```

- Force user to change password on next log in:

```bash
sudo chage --lastday 0 username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | chage: fix examples and use long arguments (#6541) | 2021-09-20T14:59:21 | [61da0633dea9](https://github.com/tldr-pages/tldr/commit/61da0633dea9e2d5f0235a82d86351bf1d11e664)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Ilya Tribusean](mailto:itribusean@fusionworks.md) | tiny improvement | 2017-12-05T08:26:18 | [f5ce198158e2](https://github.com/tldr-pages/tldr/commit/f5ce198158e22b7e7afc5fe00eb1ccb8d56afc39)
[slash3b](mailto:slash3b@gmail.com) | fixes | 2017-12-04T19:32:06 | [6453e7e98a7b](https://github.com/tldr-pages/tldr/commit/6453e7e98a7bebfc08c924d2d934c2abdb2ea571)
[slash3b](mailto:slash3b@gmail.com) | chage: add page | 2017-12-03T10:59:21 | [7e8fc327e550](https://github.com/tldr-pages/tldr/commit/7e8fc327e550a2fe101a9702830bd6ad14d11d84)

