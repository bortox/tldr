---
author: ['CTome']
date: 1658487433
title: "pyinfra"
description: "pyinfra, Automates infrastructure at a large scale."
categories: "common"
---
> More information: <https://docs.pyinfra.com>.

- Execute a command over SSH:

```bash
pyinfra target_ip_address exec -- command_name_and_arguments
```

- Execute contents of a deploy file on a list of targets:

```bash
pyinfra path/to/target_list.py path/to/deploy.py
```

- Execute commands on locally:

```bash
pyinfra @local path/to/deploy.py
```

- Execute commands over Docker:

```bash
pyinfra @docker/container path/to/deploy.py
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CTome](mailto:64846840+CrimsonTome@users.noreply.github.com) | pyinfra: add page (#8238) | 2022-07-22T12:57:13 | [2ff80e00a5a8](https://github.com/tldr-pages/tldr/commit/2ff80e00a5a81b16aed0d822180a60835f65a696)

