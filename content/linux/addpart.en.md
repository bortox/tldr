---
author: ['marchersimon', 'Jenesh Napit']
date: 1618584134
title: "addpart, TLDR Pages"
description: "addpart, Tells the Linux kernel about the existence of the specified partition."
categories: "linux"
---
> The command is a simple wrapper around the `add partition` ioctl.

> More information: <https://manned.org/addpart>.

- Tell the kernel about the existence of the specified partition:

```bash
addpart device partition start length
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Jenesh Napit](mailto:47792836+jenesh@users.noreply.github.com) | addpart: add page (#4649) | 2020-10-12T23:47:12 | [7bf5162624f7](https://github.com/tldr-pages/tldr/commit/7bf5162624f75777d47076838b547d0658a808f9)

