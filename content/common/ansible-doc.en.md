---
author: ['Natechawin Suthison']
date: 1604177074
title: "ansible-doc"
description: "ansible-doc, Display information on modules installed in Ansible libraries."
categories: "common"
---
> Display a terse listing of plugins and their short descriptions.

> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-doc.html>.

- List available action plugins (modules):

```bash
ansible-doc --list
```

- List available plugins of a specific type:

```bash
ansible-doc --type plugin_type --list
```

- Show information about a specific action plugin (module):

```bash
ansible-doc plugin_name
```

- Show information about a plugin with a specific type:

```bash
ansible-doc --type plugin_type plugin_name
```

- Show the playbook snippet for action plugin (modules):

```bash
ansible-doc --snippet plugin_name
```

- Show information about an action plugin (module) as JSON:

```bash
ansible-doc --json plugin_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Natechawin Suthison](mailto:natechawin@gmail.com) | ansible-doc: add page (#4843) | 2020-10-31T21:44:34 | [7fe92893a110](https://github.com/tldr-pages/tldr/commit/7fe92893a11086e6e7289ef367b3962c00689585)

