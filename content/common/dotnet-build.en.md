---
author: ['Ryzhehvost', 'Axel Navarro']
date: 1603906263
title: "dotnet build, TLDR Pages"
description: "dotnet build, Builds a .NET application and its dependencies."
categories: "common"
---
> More information: <https://docs.microsoft.com/dotnet/core/tools/dotnet-build>.

- Compile the project or solution in the current directory:

```bash
dotnet build
```

- Compile a .NET project or solution in debug mode:

```bash
dotnet build path/to/project_or_solution
```

- Compile in release mode:

```bash
dotnet build --configuration Release
```

- Compile without restoring dependencies:

```bash
dotnet build --no-restore
```

- Compile with a specific verbosity level:

```bash
dotnet build --verbosity quiet|minimal|normal|detailed|diagnostic
```

- Compile for a specific runtime:

```bash
dotnet build --runtime runtime_identifier
```

- Specify the output directory:

```bash
dotnet build --output path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | dotnet-build: fix compile in release mode example (#4809) | 2020-10-28T18:31:03 | [81f0b337e1fe](https://github.com/tldr-pages/tldr/commit/81f0b337e1feae71e1f0a6c69b711a2db9e7f466)
[Axel Navarro](mailto:navarroaxel@gmail.com) | dotnet-build: add page (#4340) | 2020-09-29T12:20:05 | [23cc14bc949f](https://github.com/tldr-pages/tldr/commit/23cc14bc949f8faf0dd468f0ac8c1f976ef32eee)

