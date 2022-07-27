---
author: ['teeteejo', 'marchersimon']
date: 1618584134
title: "logsave, TLDR Pages"
description: "logsave, Save the output of a command in a logfile."
categories: "linux"
---
> More information: <https://manned.org/logsave>.

- Execute command with specified argument(s) and save its output to log file:

```bash
logsave path/to/logfile command
```

- Take input from standard input and save it in a log file:

```bash
logsave logfile -
```

- Append the output to a log file, instead of replacing its current contents:

```bash
logsave -a logfile command
```

- Show verbose output:

```bash
logsave -v logfile command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[teeteejo](mailto:72230915+teeteejo@users.noreply.github.com) | logsave: add page (#4486) | 2020-10-05T17:30:14 | [414bdc2405f0](https://github.com/tldr-pages/tldr/commit/414bdc2405f02fb6c3657013911789feff19398f)

