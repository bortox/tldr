---
author: ['Carlo Mencarelli']
date: 1655651032
title: "cloud-init, TLDR Pages"
description: "cloud-init, Command line tool for managing cloud instance initialization."
categories: "linux"
---
> More information: <https://cloudinit.readthedocs.io>.

- Display the status of the most recent cloud-init run:

```bash
cloud-init status
```

- Wait for cloud-init to finish running and then report status:

```bash
cloud-init status --wait
```

- List available top-level metadata keys to query:

```bash
cloud-init query --list-keys
```

- Query cached instance metadata for data:

```bash
cloud-init query dot_delimited_variable_path
```

- Clean logs and artifacts to allow cloud-init to rerun:

```bash
cloud-init clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Carlo Mencarelli](mailto:me@carlo.cloud) | cloud-init: add page (#8139) | 2022-06-19T17:03:52 | [d9785718623d](https://github.com/tldr-pages/tldr/commit/d9785718623d5f4ab4a174302af2d2f2b93aedfa)

