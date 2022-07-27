---
author: ['Waldir Pimenta', 'Adam Herst', 'Arthur Bols', 'marchersimon']
date: 1631521281
title: "virsh, TLDR Pages"
description: "virsh, Manage virsh guest domains. (NOTE: 'guest_id' can be the id, name or UUID of the guest)."
categories: "common"
---
> Some subcommands such as `virsh list` have their own usage documentation.

> More information: <https://libvirt.org/virshcmdref.html>.

- Connect to a hypervisor session:

```bash
virsh connect qemu:///system
```

- List all domains:

```bash
virsh list --all
```

- Dump guest configuration file:

```bash
virsh dumpxml guest_id > path/to/guest.xml
```

- Create a guest from a configuration file:

```bash
virsh create path/to/config_file.xml
```

- Edit a guest's configuration file (editor can be changed with $EDITOR):

```bash
virsh edit guest_id
```

- Start/reboot/shutdown/suspend/resume a guest:

```bash
virsh command guest_id
```

- Save the current state of a guest to a file:

```bash
virsh save guest_id filename
```

- Delete a running guest:

```bash
virsh destroy guest_id && virsh undefine guest_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Adam Herst](mailto:adamherst@adamherst.com) | virsh: fix syntax of connect example (#5854) | 2021-04-29T20:02:33 | [4fb8cf891b15](https://github.com/tldr-pages/tldr/commit/4fb8cf891b15cd85045bcdddce6d7b977504c564)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Arthur Bols](mailto:arthur@bols.dev) | virsh: add page (#3241) | 2019-08-16T14:03:15 | [b4332ca6fe2a](https://github.com/tldr-pages/tldr/commit/b4332ca6fe2a524b35fc7d42973d8897ca16f631)

