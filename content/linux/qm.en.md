---
author: ['Ein Verne']
date: 1635600193
title: "qm, TLDR Pages"
description: "qm, Qemu/KVM Virtual Machine Manager."
categories: "linux"
---
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- List all virtual machines:

```bash
qm list
```

- Using an ISO file uploaded on the local storage, create a virtual machine with a 4 GB IDE disk on the `local-lvm` storage and an ID of 100:

```bash
qm create 100 -ide0 local-lvm:4 -net0 e1000 -cdrom local:iso/proxmox-mailgateway_2.1.iso
```

- Show the configuration of a virtual machine, specifying its ID:

```bash
qm config 100
```

- Start a specific virtual machine:

```bash
qm start 100
```

- Send a shutdown request, then wait until the virtual machine is stopped:

```bash
qm shutdown 100 && qm wait 100
```

- Destroy a virtual machine and remove all related resources:

```bash
qm destroy 100 --purge
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | qm, qmrestore: add page (#7157) | 2021-10-30T15:23:13 | [17c1e31309d3](https://github.com/tldr-pages/tldr/commit/17c1e31309d3a16f0ffccd215d683c947731700a)

