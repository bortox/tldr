---
author: ['Axel Navarro']
date: 1648937787
title: "dotnet tool"
description: "dotnet tool, Manage .NET tools and search published tools in NuGet."
categories: "common"
---
> More information: <https://docs.microsoft.com/dotnet/core/tools/global-tools>.

- Install a global tool (don't use `--global` for local tools):

```bash
dotnet tool install --global dotnetsay
```

- Install tools defined in the local tool manifest:

```bash
dotnet tool restore
```

- Update a specific global tool (don't use `--global` for local tools):

```bash
dotnet tool update --global tool_name
```

- Uninstall a global tool (don't use `--global` for local tools):

```bash
dotnet tool uninstall --global tool_name
```

- List installed global tools (don't use `--global` for local tools):

```bash
dotnet tool list --global
```

- Search tools in NuGet:

```bash
dotnet tool search search_term
```

- Display help:

```bash
dotnet tool --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | dotnet-tool: add page (#7769) | 2022-04-03T00:16:27 | [59f031bb0c61](https://github.com/tldr-pages/tldr/commit/59f031bb0c612d11c53397d0792934757e14affa)

