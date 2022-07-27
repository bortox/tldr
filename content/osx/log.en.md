---
author: ['James Childers']
date: 1631046914
title: "log, TLDR Pages"
description: "log, View, export, and configure logging systems."
categories: "osx"
---
> More information: <https://www.dssw.co.uk/reference/log.html>.

- Stream live system logs:

```bash
log stream
```

- Stream logs sent to `syslog` from the process with a specific PID:

```bash
log stream --process process_id
```

- Show logs sent to syslog from a process with a specific name:

```bash
log show --predicate "process == 'process_name'"
```

- Export all logs to disk for the past hour:

```bash
sudo log collect --last 1h --output path/to/file.logarchive
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[James Childers](mailto:james.childers@gmail.com) | log: add page (#6316) | 2021-09-07T22:35:14 | [cac13976b0f8](https://github.com/tldr-pages/tldr/commit/cac13976b0f8e8b74912f83c523eff0fb03f100f)

