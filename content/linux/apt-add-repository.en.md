---
author: ['Patrice Denis', 'Starbeamrainbowlabs']
date: 1618665963
title: "apt-add-repository, TLDR Pages"
description: "apt-add-repository, Manages apt repository definitions."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Add a new apt repository:

```bash
apt-add-repository repository_spec
```

- Remove an apt repository:

```bash
apt-add-repository --remove repository_spec
```

- Update the package cache after adding a repository:

```bash
apt-add-repository --update repository_spec
```

- Enable source packages:

```bash
apt-add-repository --enable-source repository_spec
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | apt-add-repository: add page (#3229) * apt-add-repository: add page * Update apt-add-repository.md | 2019-08-08T02:00:59 | [5d7595c38e76](https://github.com/tldr-pages/tldr/commit/5d7595c38e7696dcb92c6247a6d09271bffe41e3)

