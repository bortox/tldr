---
author: ['Muhammad Falak R Wani']
date: 1647836050
title: "trace-cmd, TLDR Pages"
description: "trace-cmd, Utility to interact with the Ftrace Linux kernel internal tracer."
categories: "linux"
---
> This utility only runs as root.

> More information: <https://manned.org/trace-cmd>.

- Display the status of tracing system:

```bash
trace-cmd stat
```

- List available tracers:

```bash
trace-cmd list -t
```

- Start tracing with a specific plugin:

```bash
trace-cmd start -p timerlat|osnoise|hwlat|blk|mmiotrace|function_graph|wakeup_dl|wakeup_rt|wakeup|function|nop
```

- View the trace output:

```bash
trace-cmd show
```

- Stop the tracing but retain the buffers:

```bash
trace-cmd stop
```

- Clear the trace buffers:

```bash
trace-cmd clear
```

- Clear the trace buffers and stop tracing:

```bash
trace-cmd reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | trace-cmd: add page (#7820) | 2022-03-21T05:14:10 | [f3b986941a10](https://github.com/tldr-pages/tldr/commit/f3b986941a10a45809f21225f541267cd12ee555)

