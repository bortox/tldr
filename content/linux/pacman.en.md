---
author: ['SushiDude', 'Gergely Imreh', 'Damian Poddebniak', 'Agniva De Sarker', 'rprieto', 'Axel Navarro', 'Alberto', 'lord63', 'Ruben Vereecken', 'CleanMachine1', 'marchersimon']
date: 1635127833
title: "pacman"
description: "pacman, Arch Linux package manager utility."
categories: "linux"
---
> Some subcommands such as `pacman sync` have their own usage documentation.

> More information: <https://man.archlinux.org/man/pacman.8>.

- Synchronize and update all packages:

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Install a new package:

```bash
sudo pacman --sync package_name
```

- Remove a package and its dependencies:

```bash
sudo pacman --remove --recursive package_name
```

- Search the package database for a regular expression or keyword:

```bash
pacman --sync --search "search_pattern"
```

- List installed packages and versions:

```bash
pacman --query
```

- List only the explicitly installed packages and versions:

```bash
pacman --query --explicit
```

- List orphan packages (installed as dependencies but not actually required by any package):

```bash
pacman --query --unrequired --deps --quiet
```

- Empty the entire pacman cache:

```bash
sudo pacman --sync --clean --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | pacman: use long arguments and replace -Qo example (#6083) | 2021-06-07T22:26:05 | [0314a1240935](https://github.com/tldr-pages/tldr/commit/0314a124093567a8a9c7184dacbd79904d0e8d17)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman: add more information link (#5146) | 2021-01-19T15:40:16 | [dbb0e9ef9767](https://github.com/tldr-pages/tldr/commit/dbb0e9ef97671aff87d987e2e67dce8f19d6668a)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Revert "pacman: update install instructions" This reverts commit 37ff096332183e7bc87635e9aaea70f5e25b9936. See discussion at [...] | 2017-11-27T18:23:52 | [e5d314aeebbc](https://github.com/tldr-pages/tldr/commit/e5d314aeebbc49cc910b42015fac78ad3c3e070b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | pacman: update install instructions Adding the `-u` flaf to install according to best practices https://github.com/tldr-pages/tldr/pull/1562 | 2017-10-30T05:24:50 | [37ff09633218](https://github.com/tldr-pages/tldr/commit/37ff096332183e7bc87635e9aaea70f5e25b9936)
[Damian Poddebniak](mailto:damian.poddebniak@fh-muenster.de) | changed parameter name; added quotation marks; | 2017-01-02T18:05:59 | [8d269894a2ad](https://github.com/tldr-pages/tldr/commit/8d269894a2adc00be4219bf0a89f0acb9baa2069)
[Damian Poddebniak](mailto:damian.poddebniak@fh-muenster.de) | pacman: fixed confusing example | 2017-01-02T18:05:59 | [8e483877578c](https://github.com/tldr-pages/tldr/commit/8e483877578c5f1481e101fc490b302f80559f68)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge pull request #593 from imrehg/pacman-extra linux/pacman: add more useful commands | 2016-01-05T16:02:37 | [bc367687e385](https://github.com/tldr-pages/tldr/commit/bc367687e385b276f40cd481a749c18c67ee545c)
[Gergely Imreh](mailto:imrehg@gmail.com) | linux/pacman: add more useful commands | 2016-01-05T03:21:03 | [f87170536f9b](https://github.com/tldr-pages/tldr/commit/f87170536f9b44e397137a9f8fd8341a68aa8402)
[SushiDude](mailto:sushidudeteam@gmail.com) | There is no need to have pacman force a refresh of all package lists. https://wiki.archlinux.org/index.php/Pacman#Upgrading_packages | 2015-12-29T15:47:46 | [b590b10dbd9f](https://github.com/tldr-pages/tldr/commit/b590b10dbd9f6ddf03665a94649e3692e456ff47)
[Alberto](mailto:oalbe@users.noreply.github.com) | Added command 'pacman -Qe' Hey there, I took the liberty to add the command `pacman -Qe` for listing all and only the explicitly [...] | 2015-12-29T12:20:11 | [8528cbb0d55e](https://github.com/tldr-pages/tldr/commit/8528cbb0d55e8566e1d3bb0afdc8a42a68b85290)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

