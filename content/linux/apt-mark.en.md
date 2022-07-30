---
author: ['Patrice Denis', 'Starbeamrainbowlabs']
date: 1618665963
title: "apt-mark"
description: "apt-mark, Utility to change the status of installed packages."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Mark a package as automatically installed:

```bash
sudo apt-mark auto package_name
```

- Hold a package at its current version and prevent updates to it:

```bash
sudo apt-mark hold package_name
```

- Allow a package to be updated again:

```bash
sudo apt-mark unhold package_name
```

- Show manually installed packages:

```bash
apt-mark showmanual
```

- Show held packages that aren't being updated:

```bash
apt-mark showhold
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | apt-mark: add page (#2520) | 2018-10-30T09:34:48 | [0bf0e88e0a1b](https://github.com/tldr-pages/tldr/commit/0bf0e88e0a1bab498f4866be0563bb2f8b543250)

