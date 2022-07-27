---
author: ['Adam Herst']
date: 1620761469
title: "virsh-help, TLDR Pages"
description: "virsh-help, Display information about `virsh` commands or command groups."
categories: "common"
---
> See also: `virsh`.

> More information: <https://manned.org/virsh>.

- List the `virsh` commands grouped into related categories:

```bash
virsh help
```

- List the command categories:

```bash
virsh help | grep "keyword"
```

- List the commands in a category:

```bash
virsh help category_keyword
```

- Show help for a command:

```bash
virsh help command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-help: add page (#5910) | 2021-05-11T21:31:09 | [2dc9b6b081ef](https://github.com/tldr-pages/tldr/commit/2dc9b6b081efd3f3b2987b5c7b0bc17ab78871b3)

