---
author: ['Lukas', 'Adam Herst', 'Anton Karmanov']
date: 1640387201
title: "virt-install, TLDR Pages"
description: "virt-install, Create virtual machines with libvirt and begin OS installation."
categories: "common"
---
> More information: <https://virt-manager.org/>.

- Create a virtual machine with 1 GB RAM and 12 GB storage and start a Debian installation:

```bash
virt-install --name vm_name --memory 1024 --disk path=path/to/image.qcow2,size=12 --cdrom path/to/debian.iso
```

- Create a x86-64, KVM-accelerated, UEFI-based virtual machine with the Q35 chipset, 4 GiB RAM, 16 GiB RAW storage, and start a Fedora installation:

```bash
virt-install --name vm_name --arch x86_64 --virt-type kvm --machine q35 --boot uefi --memory 4096 --disk path=path/to/image.raw,size=16 --cdrom path/to/fedora.iso
```

- Create a diskless live virtual machine without an emulated sound device or a USB controller. Don't start an installation and don't autoconnect to console but attach a cdrom to it (might be useful for when using a live CD like tails):

```bash
virt-install --name vm_name --memory 512 --disk none --controller type=usb,model=none --sound none --autoconsole none --install no_install=yes  --cdrom path/to/tails.iso
```

- Create a virtual machine with with 16 GiB RAM, 250 GiB storage, 8 cores with hyperthreading, a specific CPU topology, and a CPU model that shares most features with the host CPU:

```bash
virt-install --name vm_name --cpu host-model,topology.sockets=1,topology.cores=4,topology.threads=2 --memory 16384 --disk path=path/to/image.qcow2,size=250 --cdrom path/to/debian.iso
```

- Create a virtual machine and kickstart an automated deployment based on Fedora 35 using only remote resources (no ISO required):

```bash
virt-install --name vm_name --memory 2048 --disk path=path/to/image.qcow2,size=20 --location=https://download.fedoraproject.org/pub/fedora/linux/releases/35/Everything/x86_64/os/ --extra-args="inst.ks=https://path/to/valid/kickstart.org"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lukas](mailto:lap@refre.ch) | virt-install: update page (#7498) | 2021-12-25T00:06:41 | [bd3cc8a00504](https://github.com/tldr-pages/tldr/commit/bd3cc8a00504e751bfc7120a52df104401951960)
[Adam Herst](mailto:adamherst@adamherst.com) | virt-install: add --name option to example (#5799) Running the existing example (on Ubuntu 20.04) gives the error message: ERROR [...] | 2021-04-21T14:52:40 | [4c059df5a662](https://github.com/tldr-pages/tldr/commit/4c059df5a66283a0a7c85d653af978b21342ea06)
[Anton Karmanov](mailto:bergentroll@insiberia.net) | virt-install, virt-sparsify: add page (#4333) | 2020-09-17T13:13:29 | [50a412648531](https://github.com/tldr-pages/tldr/commit/50a4126485311813b09b0b23a1bbdcc8fb774b4a)

