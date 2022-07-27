---
author: ['Daniel']
date: 1634182296
title: "ttyplot, TLDR Pages"
description: "ttyplot, A realtime plotting utility for the command line with data input from stdin."
categories: "linux"
---
> More information: <https://github.com/tenox7/ttyplot>.

- Plot the values `1`, `2` and `3` (`cat` prevents ttyplot to exit):

```bash
{ echo 1 2 3; cat } | ttyplot
```

- Set a specific title and unit:

```bash
{ echo 1 2 3; cat } | ttyplot -t title -u unit
```

- Use a while loop to continuously plot random values:

```bash
{ while true; do echo $RANDOM; sleep 1; done } | ttyplot
```

- Parse the output from `ping` and visualize it:

```bash
ping 8.8.8.8 | sed -u 's/^.*time=//g; s/ ms//g' | ttyplot -t "ping to 8.8.8.8" -u ms
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | ttyplot: add page (#6679) | 2021-10-14T05:31:36 | [e5f8cd45376e](https://github.com/tldr-pages/tldr/commit/e5f8cd45376e5422d987dc173ab300fda9fd08e4)

