---
author: ['Jens C. Jensen']
date: 1615554802
title: "coredumpctl"
description: "coredumpctl, Retrieve and process saved core dumps and metadata."
categories: "linux"
---
> More information: <https://www.freedesktop.org/software/systemd/man/coredumpctl.html>.

- List all captured core dumps:

```bash
coredumpctl list
```

- List captured core dumps for a program:

```bash
coredumpctl list program
```

- Show information about the core dumps matching a program with `PID`:

```bash
coredumpctl info PID
```

- Invoke debugger using the last core dump of a program:

```bash
coredumpctl debug program
```

- Extract the last core dump of a program to a file:

```bash
coredumpctl --output=path/to/file dump program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jens C. Jensen](mailto:1847332+jensecj@users.noreply.github.com) | coredumpctl: add page (#5421) | 2021-03-12T14:13:22 | [1ab2f8cf3d60](https://github.com/tldr-pages/tldr/commit/1ab2f8cf3d6074f5e97f51caf3473dea029b70bb)

