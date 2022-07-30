---
author: ['marchersimon']
date: 1631999108
title: "logger"
description: "logger, Add messages to syslog (/var/log/syslog)."
categories: "common"
---
> More information: <https://manned.org/logger>.

- Log a message to syslog:

```bash
logger message
```

- Take input from stdin and log to syslog:

```bash
echo log_entry | logger
```

- Send the output to a remote syslog server running at a given port. Default port is 514:

```bash
echo log_entry | logger --server hostname --port port
```

- Use a specific tag for every line logged. Default is the name of logged in user:

```bash
echo log_entry | logger --tag tag
```

- Log messages with a given priority. Default is `user.notice`. See `man logger` for all priority options:

```bash
echo log_entry | logger --priority user.warning
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

