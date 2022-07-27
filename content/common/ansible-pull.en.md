---
author: ['Natechawin Suthison']
date: 1603911297
title: "ansible-pull, TLDR Pages"
description: "ansible-pull, Pull ansible playbooks from a VCS repo and executes them for the local host."
categories: "common"
---
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-pull.html>.

- Pull a playbook from a VCS and execute a default local.yml playbook:

```bash
ansible-pull -U repository_url
```

- Pull a playbook from a VCS and execute a specific playbook:

```bash
ansible-pull -U repository_url playbook
```

- Pull a playbook from a VCS at a specific branch and execute a specific playbook:

```bash
ansible-pull -U repository_url -C branch playbook
```

- Pull a playbook from a VCS, specify hosts file and execute a specific playbook:

```bash
ansible-pull -U repository_url -i hosts_file playbook
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Natechawin Suthison](mailto:natechawin@gmail.com) | ansible-pull: add page (#4830) | 2020-10-28T19:54:57 | [c84a806560be](https://github.com/tldr-pages/tldr/commit/c84a806560bed06d584276071ffbc23c3e4780bc)

