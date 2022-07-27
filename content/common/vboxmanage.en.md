---
author: ['gitmpr', 'Karthikeyan Vaithilingam']
date: 1652688998
title: "VBoxManage, TLDR Pages"
description: "VBoxManage, Command-line interface to VirtualBox."
categories: "common"
---
> Includes all the functionality of the GUI and more.

> More information: <https://www.virtualbox.org/manual/ch08.html#vboxmanage-intro>.

- List all VirtualBox virtual machines:

```bash
VBoxManage list vms
```

- Show information about a particular virtual machine:

```bash
VBoxManage showvminfo name|uuid
```

- Start a virtual machine:

```bash
VBoxManage startvm name|uuid
```

- Start a virtual machine in headless mode:

```bash
VBoxManage startvm name|uuid --type headless
```

- Shutdown the virtual machine and save its current state:

```bash
VBoxManage controlvm name|uuid savestate
```

- Shutdown down the virtual machine without saving its state:

```bash
VBoxManage controlvm name|uuid poweroff
```

- Update VBox extension packs:

```bash
VBoxManage extpack install --replace VboxExtensionPackFileName
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[gitmpr](mailto:89863774+gitmpr@users.noreply.github.com) | vboxmanage: fix typo in example (#8070) | 2022-05-16T10:16:38 | [9659a81dc32c](https://github.com/tldr-pages/tldr/commit/9659a81dc32ceb266274e2c5b728620c08616ba8)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | vboxmanage: move to common. (#4549) Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-07T22:30:09 | [78f98f39fe8d](https://github.com/tldr-pages/tldr/commit/78f98f39fe8dc0877b038f5269352cd936922656)

