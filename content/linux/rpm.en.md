---
author: ['derNiklaas', 'mira01', 'Muhammad Falak R Wani', 'Alois Mahdal', 'Martin Matous']
date: 1657430134
title: "rpm, TLDR Pages"
description: "rpm, RPM Package Manager."
categories: "linux"
---
> More information: <https://rpm.org/>.

- Show version of httpd package:

```bash
rpm --query httpd
```

- List versions of all matching packages:

```bash
rpm --query --all 'mariadb*'
```

- Forcibly install a package regardless of currently installed versions:

```bash
rpm --upgrade package_name.rpm --force
```

- Identify owner of a file and show version of the package:

```bash
rpm --query --file /etc/postfix/main.cf
```

- List package-owned files:

```bash
rpm --query --list kernel
```

- Show scriptlets from an RPM file:

```bash
rpm --query --package --scripts package_name.rpm
```

- Show changed, missing and/or incorrectly installed files of matching packages:

```bash
rpm --verify --all 'php-*'
```

- Display the changelog of a specific package:

```bash
rpm --query --changelog package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | rpm: add --changelog example (#8176) | 2022-07-10T07:15:34 | [6479bdea0530](https://github.com/tldr-pages/tldr/commit/6479bdea05304c7771faad706ef97d2c14dddb35)
[Martin Matous](mailto:18654729+mmatous@users.noreply.github.com) | rpm: use long arguments format (#8086) | 2022-05-12T17:32:12 | [791abd7b7841](https://github.com/tldr-pages/tldr/commit/791abd7b7841022dbf90c2ea7bc4f4af7e328115)
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | rpm: add more information link (#6754) | 2021-10-04T16:00:16 | [6e2251af4b41](https://github.com/tldr-pages/tldr/commit/6e2251af4b410910133d39ef0510b827690e2b0b)
[mira01](mailto:miroslav.cech@gooddata.com) | rpm: add install package example (#3291) | 2019-10-10T21:35:01 | [a2f19059e310](https://github.com/tldr-pages/tldr/commit/a2f19059e310c66d2345a51c6f0df0ca5964f927)
[Alois Mahdal](mailto:amahdal@redhat.com) | Work towards 25/6 rule Aim for 25 lines / 6 example limit. This also removes the problem of 2 commands per example by removing the [...] | 2016-01-21T20:16:05 | [442826f60903](https://github.com/tldr-pages/tldr/commit/442826f609039d0534db55c9dacf8cd3b3152228)
[Alois Mahdal](mailto:amahdal@redhat.com) | Fix TLDR lint issues | 2016-01-17T21:45:45 | [17fb4fc1bc57](https://github.com/tldr-pages/tldr/commit/17fb4fc1bc57d98eabf0dc386c8132977986618b)
[Alois Mahdal](mailto:amahdal@redhat.com) | Fix Vim typo | 2016-01-17T21:42:24 | [4192235e4170](https://github.com/tldr-pages/tldr/commit/4192235e41702b34f36d1b51b601a6458746b1c5)
[Alois Mahdal](mailto:amahdal@redhat.com) | Add page for `rpm` - RPM Package Manager | 2016-01-17T21:36:16 | [1461dcb52d8d](https://github.com/tldr-pages/tldr/commit/1461dcb52d8d43d7c6c067019a46ee8bf4c99f8b)

