---
author: ['Ein Verne', 'Managor', 'marchersimon']
date: 1618584134
title: "iotop"
description: "iotop, Display a table of current I/O usage by processes or threads."
categories: "common"
---
> More information: <https://manned.org/iotop>.

- Start top-like I/O monitor:

```bash
sudo iotop
```

- Show only processes or threads actually doing I/O:

```bash
sudo iotop --only
```

- Show I/O usage in non-interactive mode:

```bash
sudo iotop --batch
```

- Show only I/O usage of processes (default is to show all threads):

```bash
sudo iotop --processes
```

- Show I/O usage of given PID(s):

```bash
sudo iotop --pid=PID
```

- Show I/O usage of a given user:

```bash
sudo iotop --user=user
```

- Show accumulated I/O instead of bandwidth:

```bash
sudo iotop --accumulated
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Managor](mailto:42655600+Managor@users.noreply.github.com) | iotop: add sudo to all commands (#5267) | 2021-02-19T00:18:02 | [5f98c903afac](https://github.com/tldr-pages/tldr/commit/5f98c903afac85653bc9e5a9d1f652e3670481ce)
[Ein Verne](mailto:einverne@gmail.com) | iotop: add page (#3454) | 2019-10-23T21:07:21 | [1c150fd6618e](https://github.com/tldr-pages/tldr/commit/1c150fd6618e3983f142e5d2c95eb47627af1c68)

