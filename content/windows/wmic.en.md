---
author: ['Rowan']
date: 1601635178
title: "wmic"
description: "wmic, Interactive shell for detailed information about running processes."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/wmic>.

- Fundamental grammar:

```bash
wmic alias where_clause verb_clause
```

- Show brief details about the currently running processes:

```bash
wmic process list brief
```

- Show full details about the currently running processes:

```bash
wmic process list full
```

- Access specific fields such as process name, process ID and parent process ID:

```bash
wmic process get name,processid,parentprocessid
```

- Display information about a specific process:

```bash
wmic process where name="example.exe" list full
```

- Display specific fields for a specific process:

```bash
wmic process where processid=pid get name,commandline
```

- Kill a process:

```bash
wmic process pid delete
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rowan](mailto:42702037+Rowanyeet@users.noreply.github.com) | wmic: fix typo (#4411) | 2020-10-02T12:39:38 | [d744f9416166](https://github.com/tldr-pages/tldr/commit/d744f94161665fbfba4e8a6ec7b0e3643d38bd38)
[Rowan](mailto:42702037+Rowanyeet@users.noreply.github.com) | wmic: add page (#4383) | 2020-10-01T22:32:41 | [61484ccb4460](https://github.com/tldr-pages/tldr/commit/61484ccb44600c4ce1948bb39cc7c7a678a722b8)

