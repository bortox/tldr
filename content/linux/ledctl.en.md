---
author: ['Danesh Manoharan']
date: 1650150897
title: "ledctl, TLDR Pages"
description: "ledctl, Intel(R) Enclosure LED Control Application."
categories: "linux"
---
> More information: <https://manned.org/ledctl>.

- Turn on the "Locate" LED for specified device(s):

```bash
sudo ledctl locate=/dev/sda,/dev/sdb,...
```

- Turn off the "Locate" LED for specified device(s):

```bash
sudo ledctl locate_off=/dev/sda,/dev/sdb,...
```

- Turn off the "Status" LED and "Failure" LED for specified device(s):

```bash
sudo ledctl off=/dev/sda,/dev/sdb,...
```

- Turn off the "Status" LED, "Failure" LED and "Locate" LED for specified device(s):

```bash
sudo ledctl normal=/dev/sda,/dev/sdb,...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Danesh Manoharan](mailto:danesh.manoharan@gmail.com) | ledctl: add page (#7776) | 2022-04-17T01:14:57 | [8627e2396434](https://github.com/tldr-pages/tldr/commit/8627e239643428131693d665bb2b7f166ae66a59)

