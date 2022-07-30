---
author: ['Starbeamrainbowlabs', 'Waldir Pimenta', 'derNiklaas', 'Seth Falco']
date: 1656325392
title: "zramctl"
description: "zramctl, Setup and control zram devices."
categories: "linux"
---
> Use `mkfs` or `mkswap` to format zram devices to partitions.

> More information: <https://manned.org/zramctl>.

- Check if zram is enabled:

```bash
lsmod | grep -i zram
```

- Enable zram with a dynamic number of devices (use `zramctl` to configure devices further):

```bash
sudo modprobe zram
```

- Enable zram with exactly 2 devices:

```bash
sudo modprobe zram num_devices=2
```

- Find and initialize the next free zram device to a 2 GB virtual drive using LZ4 compression:

```bash
sudo zramctl --find --size 2GB --algorithm lz4
```

- List currently initialized devices:

```bash
zramctl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | zenity, zgrep, zramctl: add more information link (#6758) | 2021-10-04T06:00:39 | [c05f245fd530](https://github.com/tldr-pages/tldr/commit/c05f245fd530f6134b91568ae3d0181a74c6814b)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | zramctl: improve module loading examples (#3870) * zramctl: improve module loading examples * zramctl: update see also equivalent * [...] | 2020-02-28T14:34:55 | [cd357a2b0372](https://github.com/tldr-pages/tldr/commit/cd357a2b037274ad9d501009c2e5627e0785cdb6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | zramctl: minor capitalization / punctuation tweaks | 2017-04-15T13:48:03 | [292825cfe7b1](https://github.com/tldr-pages/tldr/commit/292825cfe7b15e62260da1d592b2dec155605761)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | zramctl: add page (#1307) | 2017-04-07T05:26:00 | [9059d62b22fd](https://github.com/tldr-pages/tldr/commit/9059d62b22fd631c73abb6858ba360a49b04cb2e)

