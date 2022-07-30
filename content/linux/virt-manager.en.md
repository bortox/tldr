---
author: ['bl-ue']
date: 1621541621
title: "virt-manager"
description: "virt-manager, CLI launcher for virt-manager, a desktop user interface for managing KVM and Xen virtual machines and LXC containers."
categories: "linux"
---
> More information: <https://manpages.ubuntu.com/manpages/man1/virt-manager.1.html>.

- Launch virt-manager:

```bash
virt-manager
```

- Connect to a hypervisor:

```bash
virt-manager --connect hypervisor_uri
```

- Don't fork virt-manager process into background on startup:

```bash
virt-manager --no-fork
```

- Print debug output:

```bash
virt-manager --debug
```

- Open the "New VM" wizard:

```bash
virt-manager --show-domain-creator
```

- Show domain details window:

```bash
virt-manager --show-domain-editor name|id|uuid
```

- Show domain performance window:

```bash
virt-manager --show-domain-performance name|id|uuid
```

- Show connection details window:

```bash
virt-manager --show-host-summary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | virt-manager: add page (#5423) | 2021-03-12T16:23:02 | [a1aed23c7fba](https://github.com/tldr-pages/tldr/commit/a1aed23c7fba354efd77dc7ee0d0bb8b593a3929)

