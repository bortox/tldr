---
author: ['Axel Navarro']
date: 1601488799
title: "dotnet restore, TLDR Pages"
description: "dotnet restore, Restores the dependencies and tools of a .NET project."
categories: "common"
---
> More information: <https://docs.microsoft.com/dotnet/core/tools/dotnet-restore>.

- Restore dependencies for a .NET project or solution in the current directory:

```bash
dotnet restore
```

- Restore dependencies for a .NET project or solution in a specific location:

```bash
dotnet restore path/to/project_or_solution
```

- Restore dependencies without caching the HTTP requests:

```bash
dotnet restore --no-cache
```

- Force all dependencies to be resolved even if the last restore was successful:

```bash
dotnet restore --force
```

- Restore dependencies using package source failures as warnings:

```bash
dotnet restore --ignore-failed-sources
```

- Restore dependencies with a specific verbosity level:

```bash
dotnet restore --verbosity quiet|minimal|normal|detailed|diagnostic
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | dotnet restore: add page (#4341) | 2020-09-30T19:59:59 | [21586f40d884](https://github.com/tldr-pages/tldr/commit/21586f40d8845161d3139fd3901e8bf3590e330a)

