---
author: ['marchersimon']
date: 1621728415
title: "pio remote, TLDR Pages"
description: "pio remote, Helper command for PlatformIO Remote Development."
categories: "common"
---
> `pio remote [command]` takes the same arguments as its locally executing counterpart `pio [command]`.

> More information: <https://docs.platformio.org/en/latest/core/userguide/remote/index.html>.

- List all active Remote Agents:

```bash
pio remote agent list
```

- Start a new Remote Agent with a specific name and share it with friends:

```bash
pio remote agent start --name agent_name --share example1@example.com --share example2@example.com
```

- List devices from specified Agents (omit `--agent` to specify all Agents):

```bash
pio remote --agent agent_name1 --agent agent_name2 device list
```

- Connect to the serial port of a remote device:

```bash
pio remote --agent agent_name device monitor
```

- Run all targets on a specified Agent:

```bash
pio remote --agent agent_name run
```

- Update installed core packages, development platforms and global libraries on a specific Agent:

```bash
pio remote --agent agent_name update
```

- Run all tests in all environments on a specific Agent:

```bash
pio remote --agent agent_name test
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-remote: add page (#5902) * pio-remote: add page * Add second friend * Apply suggestions from code review * remove "usually" from [...] | 2021-05-23T02:06:55 | [19853b03f1a8](https://github.com/tldr-pages/tldr/commit/19853b03f1a89a8ff3b3a97f35ee8a8e4df6ab12)

