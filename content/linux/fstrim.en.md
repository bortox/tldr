---
author: ['Stig124', 'Starbeamrainbowlabs']
date: 1625841955
title: "fstrim"
description: "fstrim, Discard unused blocks on a mounted filesystem."
categories: "linux"
---
> Only supported by flash memory devices such as SSDs and microSD cards.

> More information: <https://manned.org/fstrim>.

- Trim unused blocks on all mounted partitions that support it:

```bash
sudo fstrim --all
```

- Trim unused blocks on a specified partition:

```bash
sudo fstrim /
```

- Display statistics after trimming:

```bash
sudo fstrim --verbose /
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | fstrim: add page | 2019-06-24T16:10:53 | [9de9248a4685](https://github.com/tldr-pages/tldr/commit/9de9248a4685b4466c09ce1b7adbf0e699ba00df)

