---
author: ['marchersimon']
date: 1617187951
title: "runsvdir"
description: "runsvdir, Run an entire directory of services."
categories: "common"
---
> More information: <https://manpages.ubuntu.com/manpages/latest/man8/runsvdir.8.html>.

- Start and manage all services in a directory as the current user:

```bash
runsvdir path/to/services
```

- Start and manage all services in a directory as root:

```bash
sudo runsvdir path/to/services
```

- Start services in separate sessions:

```bash
runsvdir -P path/to/services
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | runit, runsv, runsvdir, runsvchdir, sv: add more information link and move to common/ (#5648) | 2021-03-31T12:52:31 | [d562842e08a9](https://github.com/tldr-pages/tldr/commit/d562842e08a9fb8d1c71eb165394132acd5d9b3f)

