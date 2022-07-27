---
author: ['Seth Falco', 'Daniel']
date: 1656325392
title: "goaccess, TLDR Pages"
description: "goaccess, An open source real-time web log analyzer."
categories: "linux"
---
> More information: <https://goaccess.io>.

- Analyze one or more log files in interactive mode:

```bash
goaccess path/to/logfile1 path/to/file2 ...
```

- Use a specific log-format (or pre-defined formats like "combined"):

```bash
goaccess path/to/logfile --log-format=format
```

- Analyze a log from stdin:

```bash
tail -f path/to/logfile | goaccess -
```

- Analyze a log and write it to an HTML file in real-time:

```bash
goaccess path/to/logfile --output path/to/file.html --real-time-html
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | goaccess: add page (#6666) | 2021-10-06T12:20:40 | [18a94611b420](https://github.com/tldr-pages/tldr/commit/18a94611b420ae5a6d17352b1200f2743ca80563)

