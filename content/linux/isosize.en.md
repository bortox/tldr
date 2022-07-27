---
author: ['en1gma713', 'bl-ue', 'marchersimon']
date: 1618584134
title: "isosize, TLDR Pages"
description: "isosize, Display the size of an ISO file."
categories: "linux"
---
> More information: <https://manned.org/isosize>.

- Display the size of an ISO file:

```bash
isosize path/to/file.iso
```

- Display the block count and block size of an ISO file:

```bash
isosize --sectors path/to/file.iso
```

- Display the size of an ISO file divided by a given number (only usable when --sectors is not given):

```bash
isosize --divisor=number path/to/file.iso
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[en1gma713](mailto:60906502+en1gma713@users.noreply.github.com) | isosize: add page (#4522) | 2020-10-06T22:39:49 | [05964eb1710b](https://github.com/tldr-pages/tldr/commit/05964eb1710b10bae837dd87792e3dfdbc0feeca)

