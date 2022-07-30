---
author: ['Adam Herst']
date: 1618537632
title: "ansible-inventory"
description: "ansible-inventory, Display or dump an Ansible inventory."
categories: "common"
---
> See also: `ansible`.

> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-inventory.html>.

- Display the default inventory:

```bash
ansible-inventory --list
```

- Display a custom inventory:

```bash
ansbile-inventory --list --inventory path/to/file_or_script_or_directory
```

- Display the default inventory in YAML:

```bash
ansible-inventory --list --yaml
```

- Dump the default inventory to a file:

```bash
ansible-inventory --list --output path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | ansible-inventory: add page (#5756) | 2021-04-16T03:47:12 | [5bc4c97786cd](https://github.com/tldr-pages/tldr/commit/5bc4c97786cd2e049b2467bbc7dbd78691661723)

