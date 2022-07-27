---
author: ['Raul Piraces Alastuey']
date: 1633282341
title: "az bicep, TLDR Pages"
description: "az bicep, Bicep CLI command group."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/bicep>.

- Install Bicep CLI:

```bash
az bicep install
```

- Build a Bicep file:

```bash
az bicep build --file path/to/file.bicep
```

- Attempt to decompile an ARM template file to a Bicep file:

```bash
az bicep decompile --file path/to/template_file.json
```

- Upgrade Bicep CLI to the latest version:

```bash
az bicep upgrade
```

- Display the installed version of Bicep CLI:

```bash
az bicep version
```

- List all available versions of Bicep CLI:

```bash
az bicep list-versions
```

- Uninstall Bicep CLI:

```bash
az bicep uninstall
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raul Piraces Alastuey](mailto:raul.piraces@gmail.com) | az-bicep: fix incorrect more information URL (#6721) | 2021-10-03T19:32:21 | [e9c0157f5bf6](https://github.com/tldr-pages/tldr/commit/e9c0157f5bf6faf43d756ee3f08b018de4ba19fd)
[Raul Piraces Alastuey](mailto:raul.piraces@gmail.com) | az-bicep: add page (#6718) | 2021-10-03T15:17:39 | [033dbac25466](https://github.com/tldr-pages/tldr/commit/033dbac254668bc68bf57ca1b758d853180e5100)

