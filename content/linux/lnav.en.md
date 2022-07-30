---
author: ['Amit Sharma']
date: 1634003863
title: "lnav"
description: "lnav, Advanced log file viewer to analyze logs with little to no setup."
categories: "linux"
---
> More information: <https://docs.lnav.org/en/latest/cli.html>.

- View logs of a program, specifying log files, directories or URLs:

```bash
lnav path/to/log_or_directory|url
```

- View logs of a specific remote host (SSH passwordless login required):

```bash
lnav ssh user@host1.example.com:/var/log/syslog.log
```

- Validate the format of log files against the configuration and report any errors:

```bash
lnav -C path/to/log_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Amit Sharma](mailto:amitsharma928@gmail.com) | lnav: add page (#6613) | 2021-10-12T03:57:43 | [7e29a9a718d3](https://github.com/tldr-pages/tldr/commit/7e29a9a718d309671509afc9ab52b1274578b4c7)

