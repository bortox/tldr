---
author: ['Marco Bonelli', 'Starbeamrainbowlabs']
date: 1559564381
title: "collectd, TLDR Pages"
description: "collectd, System statistics collection daemon."
categories: "linux"
---
> More information: <https://collectd.org/>.

- Show usage help, including the program version:

```bash
collectd -h
```

- Test the configuration file and then exit:

```bash
collectd -t
```

- Test plugin data collection functionality and then exit:

```bash
collectd -T
```

- Start collectd:

```bash
collectd
```

- Specify a custom configuration file location:

```bash
collectd -C path/to/file
```

- Specify a custom PID file location:

```bash
collectd -P path/to/file
```

- Don't fork into the background:

```bash
collectd -f
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | collectd: add page (#3055) | 2019-05-28T01:52:36 | [251cb0d26c18](https://github.com/tldr-pages/tldr/commit/251cb0d26c18746c6380a7179e0755f8ec72a72a)

