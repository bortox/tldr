---
author: ['bl-ue', 'pxgamer', 'Galdin Raphael', 'Seth Falco', 'marchersimon']
date: 1631521281
title: "dotnet, TLDR Pages"
description: "dotnet, Cross platform .NET command-line tools for .NET Core."
categories: "common"
---
> Some subcommands such as `dotnet build` have their own usage documentation.

> More information: <https://docs.microsoft.com/dotnet/core/tools>.

- Initialize a new .NET project:

```bash
dotnet new template_short_name
```

- Restore NuGet packages:

```bash
dotnet restore
```

- Build and execute the .NET project in the current directory:

```bash
dotnet run
```

- Run a packaged dotnet application (only needs the runtime, the rest of the commands require the .NET Core SDK installed):

```bash
dotnet path/to/application.dll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | dotnet: add link to homepage | 2019-06-09T06:54:24 | [5050c2cbd7dc](https://github.com/tldr-pages/tldr/commit/5050c2cbd7dce54105b7de8f5d6262ca6c8684ca)
[Galdin Raphael](mailto:gldraphael@users.noreply.github.com) | dotnet: add page (#1581) | 2017-10-29T14:26:14 | [90fe67325ea6](https://github.com/tldr-pages/tldr/commit/90fe67325ea6036929a4fa975fed35451a97f07e)

