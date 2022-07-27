---
author: ['Managor']
date: 1643508457
title: "pw-link, TLDR Pages"
description: "pw-link, Manage links between ports in PipeWire."
categories: "linux"
---
> More information: <https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Virtual-Devices>.

- List all audio output and input ports:

```bash
pw-link --output --input'
```

- Create a link between an output and an input port:

```bash
pw-link output_port_name input_port_name
```

- Disconnect two ports:

```bash
pw-link --disconnect output_port_name input_port_name
```

- Display help:

```bash
pw-link -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pw-link: add page (#7703) | 2022-01-30T03:07:37 | [3c192db1c4ce](https://github.com/tldr-pages/tldr/commit/3c192db1c4ce0df19abb913b92ca756f00be7d57)

