---
author: ['meowmeowcat', 'Emily Grace Seville', 'Peter Tripp', 'rprieto', 'pixel', 'Srinivasan R', 'Seth Falco', 'Ruben Vereecken']
date: 1645164327
title: "systemsetup"
description: "systemsetup, Configure System Preferences machine settings."
categories: "osx"
---
> More information: <https://support.apple.com/guide/remote-desktop/about-systemsetup-apd95406b8d/mac>.

- Enable remote login (SSH):

```bash
systemsetup -setremotelogin on
```

- Specify timezone, NTP Server and enable network time:

```bash
systemsetup -settimezone "US/Pacific" -setnetworktimeserver us.pool.ntp.org -setusingnetworktime on
```

- Make the machine never sleep and automatically restart on power failure or kernel panic:

```bash
systemsetup -setsleep off -setrestartpowerfailure on -setrestartfreeze on
```

- List valid startup disks:

```bash
systemsetup -liststartupdisks
```

- Specify a new startup disk:

```bash
systemsetup -setstartupdisk path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | systemsetup: fix more information link (#7755) | 2022-02-18T07:05:27 | [a1dca9579cae](https://github.com/tldr-pages/tldr/commit/a1dca9579cae01e973da69735dad78744373237c)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Peter Tripp](mailto:petertripp@gmail.com) | Linting fixes. | 2016-01-20T12:52:51 | [f36e1216811a](https://github.com/tldr-pages/tldr/commit/f36e1216811ad449019c9fd2bc361cb2a0208894)
[Peter Tripp](mailto:petertripp@gmail.com) | systemsetup: combine the seperate examples. The options are super self-documenting and very helpful together. | 2016-01-20T12:47:48 | [88b6cb879d6f](https://github.com/tldr-pages/tldr/commit/88b6cb879d6fd9d0c23f08cff0dbadd01098172e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Add extra newline between consecutive commands examples. These 6 files had multiple examples all separated by a single newline. While [...] | 2015-10-28T18:10:44 | [2097cf359d9b](https://github.com/tldr-pages/tldr/commit/2097cf359d9bc97448a1dceb5b9549426159ea69)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

