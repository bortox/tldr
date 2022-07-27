---
author: ['Axel Navarro', 'bl-ue', 'Owen Voke']
date: 1610307737
title: "dotnet publish, TLDR Pages"
description: "dotnet publish, Publish a .NET application and its dependencies to a directory for deployment to a hosting system."
categories: "common"
---
> More information: <https://docs.microsoft.com/dotnet/core/tools/dotnet-publish>.

- Compile a .NET project in release mode:

```bash
dotnet publish --configuration Release path/to/project_file
```

- Publish the .NET Core runtime with your application for the specified runtime:

```bash
dotnet publish --self-contained true --runtime runtime_identifier path/to/project_file
```

- Package the application into a platform-specific single-file executable:

```bash
dotnet publish --runtime runtime_identifier -p:PublishSingleFile=true path/to/project_file
```

- Trim unused libraries to reduce the deployment size of an application:

```bash
dotnet publish --self-contained true --runtime runtime_identifier -p:PublishTrimmed=true path/to/project_file
```

- Compile a .NET project without restoring dependencies:

```bash
dotnet publish --no-restore path/to/project_file
```

- Specify the output directory:

```bash
dotnet publish --output path/to/directory path/to/project_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dotnet-publish: change folder to directory | 2021-01-10T20:42:17 | [36f7d8e2e5bb](https://github.com/tldr-pages/tldr/commit/36f7d8e2e5bb43ae1f1db34069c8b17286a5404b)
[Owen Voke](mailto:development@voke.dev) | dotnet-publish: remove locale from page url | 2020-09-22T19:06:55 | [0c4e7745b82a](https://github.com/tldr-pages/tldr/commit/0c4e7745b82af8d309d439051905b9a8d03049b1)
[Axel Navarro](mailto:navarroaxel@gmail.com) | dotnet-publish: add page (#4321) | 2020-09-11T02:33:43 | [b3d41f71e28a](https://github.com/tldr-pages/tldr/commit/b3d41f71e28a2abacfb11a37ee6ba62846513d1c)

