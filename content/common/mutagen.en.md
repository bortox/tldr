---
author: ['Pierre Rudloff']
date: 1616955521
title: "mutagen"
description: "mutagen, Real-time file synchronization and network forwarding tool."
categories: "common"
---
> More information: <https://mutagen.io>.

- Start a synchronization session between a local directory and a remote host:

```bash
mutagen sync create --name=session_name /path/to/local/directory/ user@host:/path/to/remote/directory/
```

- Start a synchronization session between a local directory and a Docker container:

```bash
mutagen sync create --name=session_name /path/to/local/directory/ docker://user@container_name/path/to/remote/directory/
```

- Stop a running session:

```bash
mutagen sync terminate session_name
```

- Start a project:

```bash
mutagen project start
```

- Stop a project:

```bash
mutagen project terminate
```

- List running sessions for the current project:

```bash
mutagen project list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | mutagen: add page (#5493) | 2021-03-28T20:18:41 | [2e1d5f551c65](https://github.com/tldr-pages/tldr/commit/2e1d5f551c652c3039d0820f597ac1f45ebe5c9d)

