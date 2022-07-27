---
author: ['Lars Maier']
date: 1562360563
title: "rr, TLDR Pages"
description: "rr, Debugging tool designed to record and replay program execution."
categories: "common"
---
> More information: <https://rr-project.org/>.

- Record an application:

```bash
rr record path/to/binary --arg1 --arg2
```

- Replay latest recorded execution:

```bash
rr replay
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lars Maier](mailto:lars@arangodb.com) | rr: add page (#3166) | 2019-07-05T23:02:43 | [dacfef89ace9](https://github.com/tldr-pages/tldr/commit/dacfef89ace9e3da64a369e3fbc8977d5a98f2a7)

