---
author: ['Waldir Pimenta', 'Sanhu Li', 'Reinhart Previano Koentjoro', 'Angelos Orfanakos', 'Fürbringer', 'Starbeamrainbowlabs', 'thenarcissist', 'Patrice Denis']
date: 1641608133
title: "apt"
description: "apt, Package management utility for Debian based distributions."
categories: "linux"
---
> Recommended replacement for `apt-get` when used interactively in Ubuntu versions 16.04 and later.

> More information: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Update the list of available packages and versions (it's recommended to run this before other `apt` commands):

```bash
sudo apt update
```

- Search for a given package:

```bash
apt search package
```

- Show information for a package:

```bash
apt show package
```

- Install a package, or update it to the latest available version:

```bash
sudo apt install package
```

- Remove a package (using `purge` instead also removes its configuration files):

```bash
sudo apt remove package
```

- Upgrade all installed packages to their newest available versions:

```bash
sudo apt upgrade
```

- List all packages:

```bash
apt list
```

- List installed packages:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | apt: update 2nd description line as per discussion. Link: https://github.com/tldr-pages/tldr/pull/2361#discussion_r323767992 | 2019-09-15T01:39:36 | [cd3a80bffbd3](https://github.com/tldr-pages/tldr/commit/cd3a80bffbd3f6c26c39e9513b5e072f58c9ddfa)
[thenarcissist](mailto:35285981+thenarcissist@users.noreply.github.com) | apt: added to description. Added that apt should be preferred over apt-get in Ubuntu systems which are 16.04 and later. | 2019-09-15T01:39:36 | [b6e405f0ee83](https://github.com/tldr-pages/tldr/commit/b6e405f0ee83826c7378b55c2caeb2466268a6b6)
[Sanhu Li](mailto:lisanhu@users.noreply.github.com) | apt: add package listing examples (#2945) | 2019-04-24T14:01:22 | [668c26887ba6](https://github.com/tldr-pages/tldr/commit/668c26887ba6ab9532ce02818ef5ef2b8908d765)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | apt-get: add example for upgrading a single package (#1500) | 2017-09-23T12:27:18 | [0d6202fa8981](https://github.com/tldr-pages/tldr/commit/0d6202fa8981b496d82fdd6d1704531262e9511e)
[Angelos Orfanakos](mailto:me@agorf.gr) | apt: add missing sudo to examples | 2017-04-23T22:55:19 | [80bb5124917f](https://github.com/tldr-pages/tldr/commit/80bb5124917fb1be4092b9ca3825b6e99bc1fa7b)
[Angelos Orfanakos](mailto:me@agorf.gr) | apt: remove full-upgrade example It's rarely used and beyond the scope of tldr | 2017-04-23T22:55:19 | [1516784640b3](https://github.com/tldr-pages/tldr/commit/1516784640b3029a71498c609cd8a830c61e30bc)
[Angelos Orfanakos](mailto:me@agorf.gr) | apt: add show example | 2017-04-23T22:55:19 | [73d3ddabc13a](https://github.com/tldr-pages/tldr/commit/73d3ddabc13a4cc4126aa22a760833a6621e4662)
[Angelos Orfanakos](mailto:me@agorf.gr) | apt: remove invalid autoremove example There is no autoremove command | 2017-04-23T22:55:19 | [fd6104b2909f](https://github.com/tldr-pages/tldr/commit/fd6104b2909fc161bd5e79ec9f05188920ed8e29)
[Fürbringer](mailto:severin@protonmail.ch) | apt: add page (#1205) | 2016-12-22T00:09:01 | [c07f9624f9ae](https://github.com/tldr-pages/tldr/commit/c07f9624f9ae7d24688834a67e055a175d7adb81)

