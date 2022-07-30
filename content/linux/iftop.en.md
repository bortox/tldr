---
author: ['Ein Verne', 'marchersimon']
date: 1618584134
title: "iftop"
description: "iftop, Show bandwidth usage on an interface by host."
categories: "linux"
---
> More information: <https://manned.org/iftop>.

- Show the bandwidth usage:

```bash
sudo iftop
```

- Show the bandwidth usage of a given interface:

```bash
sudo iftop -i interface
```

- Show the bandwidth usage with port information:

```bash
sudo iftop -P
```

- Do not show bar graphs of traffic:

```bash
sudo iftop -b
```

- Do not look up hostnames:

```bash
sudo iftop -n
```

- Get help about interactive commands:

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Ein Verne](mailto:einverne@gmail.com) | iftop: add page (#3459) | 2019-10-27T17:44:37 | [17437a8401d8](https://github.com/tldr-pages/tldr/commit/17437a8401d87f2853ecc32841ce88e318d99006)

