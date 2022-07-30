---
author: ['Ayush Dwivedi', 'Stig124']
date: 1625841955
title: "bmon"
description: "bmon, Monitor bandwidth and capture network related statistics."
categories: "linux"
---
> More information: <https://github.com/tgraf/bmon>.

- Display the list of all the interfaces:

```bash
bmon -a
```

- Display data transfer rates in bits per second:

```bash
bmon -b
```

- Set policy to define which network interface(s) is/are displayed:

```bash
bmon -p interface_1,interface_2,interface_3
```

- Set interval (in seconds) in which rate per counter is calculated:

```bash
bmon -R 2.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Ayush Dwivedi](mailto:itsayushdwivedi@gmail.com) | bmon: add page (#1582) | 2017-11-13T18:47:57 | [7cca3702370f](https://github.com/tldr-pages/tldr/commit/7cca3702370f3839670d4c295b69f20acb0239c2)

