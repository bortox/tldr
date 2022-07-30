---
author: ['Ishaan Bhimwal', 'bl-ue', 'Antonio Bustos']
date: 1658240132
title: "htpdate"
description: "htpdate, Synchronize local date and time via HTTP headers from web servers."
categories: "linux"
---
> More information: <http://www.vervest.org/htp/>.

- Synchronize date and time:

```bash
sudo htpdate host
```

- Perform simulation of synchronization, without any action:

```bash
htpdate -q host
```

- Compensate the systematic clock drift:

```bash
sudo htpdate -x host
```

- Set time immediate after the synchronization:

```bash
sudo htpdate -s host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Antonio Bustos](mailto:antoniobusrod@users.noreply.github.com) | htpdate: add page (#4479) | 2020-10-10T04:36:17 | [b727765b1586](https://github.com/tldr-pages/tldr/commit/b727765b15864c6c922f9af6e0fb7427344cfc11)

