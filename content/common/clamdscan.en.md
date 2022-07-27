---
author: ['EduardBaer']
date: 1633816825
title: "clamdscan, TLDR Pages"
description: "clamdscan, A command-line virus scanner using the ClamAV Daemon."
categories: "common"
---
> More information: <https://www.clamav.net>.

- Scan a file or directory for vulnerabilities:

```bash
clamdscan path/to/file_or_directory
```

- Scan data from stdin:

```bash
command | clamdscan -
```

- Scan the current directory and output only infected files:

```bash
clamdscan --infected
```

- Output the scan report to a log file:

```bash
clamdscan --log path/to/log_file
```

- Move infected files to a specific directory:

```bash
clamdscan --move path/to/quarantine_directory
```

- Remove infected files:

```bash
clamdscan --remove
```

- Use multiple threads to scan a directory:

```bash
clamdscan --multiscan
```

- Pass the file descriptor instead of streaming the file to the daemon:

```bash
clamdscan --fdpass
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[EduardBaer](mailto:EduardBaer@users.noreply.github.com) | clamdscan: add page (#6877) | 2021-10-10T00:00:25 | [5cf203152004](https://github.com/tldr-pages/tldr/commit/5cf203152004ee5a277d428fb77c058f883fb5b3)

