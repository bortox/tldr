---
author: ['Adrien Thebo']
date: 1660057375
title: "rpm-ostree"
description: "rpm-ostree, A hybrid image/package system."
categories: "linux"
---
> Manage ostree deployments, package layers, filesystem overlays, and boot configuration.

> More information: <https://coreos.github.io/rpm-ostree/administrator-handbook/>.

- Show rpm-ostree deployments in the order they will appear in the bootloader:

```bash
rpm-ostree status
```

- Show packages which are outdated and can be updated:

```bash
rpm-ostree upgrade --preview
```

- Prepare a new ostree deployment with upgraded packages and reboot into it:

```bash
rpm-ostree upgrade --reboot
```

- Reboot into the previous ostree deployment:

```bash
rpm-ostree rollback --reboot
```

- Install a package into a new ostree deployment and reboot into it:

```bash
rpm-ostree install package --reboot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | rpm-ostree: add page (#8277) * rpm-ostree: add page * rpm-ostree: amend example description wording Co-authored-by: CleanMachine1 [...] | 2022-08-09T17:02:55 | [e61129519756](https://github.com/tldr-pages/tldr/commit/e61129519756b23d1573d0b3c0cc2fb75ec35372)

