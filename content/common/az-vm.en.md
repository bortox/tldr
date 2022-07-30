---
author: ['a1346054', 'Muhammad Falak R Wani']
date: 1631763133
title: "az vm"
description: "az vm, Manage virtual machines in Azure."
categories: "common"
---
> Part of `az`, the command-line client for Microsoft Azure.

> More information: <https://docs.microsoft.com/cli/azure/vm>.

- List details of available Virtual Machines:

```bash
az vm list
```

- Create an `UbuntuServer 18.04 LTS` Virtual Machine and generate ssh keys:

```bash
az vm create --resource-group rg --name vm_name --image Canonical:UbuntuServer:18.04-LTS:latest --admin-user azureuser --generate-ssh-keys
```

- Stop a Virtual Machine:

```bash
az vm stop --resource-group rg --name vm_name
```

- Deallocate a Virtual Machine:

```bash
az vm deallocate --resource-group rg --name vm_name
```

- Start a Virtual Machine:

```bash
az vm start --resource-group rg --name vm_name
```

- Restart a Virtual Machine:

```bash
az vm restart --resource-group rg --name vm_name
```

- List VM images available in the Azure Marketplace:

```bash
az vm image list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[a1346054](mailto:36859588+a1346054@users.noreply.github.com) | *: shellcheck and fix typos (#6526) * test.sh: quote a variable * contributing-guides/*: fix typos * pages/*: fix typos * scripts/*: [...] | 2021-09-16T05:32:13 | [5c62e303b5ab](https://github.com/tldr-pages/tldr/commit/5c62e303b5ab7c0f38b360c3918380ccd011a536)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | az-vm: use az instead of azure-cli (#6244) | 2021-07-18T21:34:12 | [81d1bb75d1b6](https://github.com/tldr-pages/tldr/commit/81d1bb75d1b67975ff22fe94df14a96284e32da2)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | az-vm: add page (#6222) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Signed-off-by: Muhammad Falak R [...] | 2021-07-16T11:52:37 | [9d221a36b7f0](https://github.com/tldr-pages/tldr/commit/9d221a36b7f0da89e4ab2c14f9a07b5c8ebc8835)

