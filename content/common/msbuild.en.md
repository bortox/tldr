---
author: ['Owen Voke', 'pxgamer']
date: 1559676580
title: "msbuild"
description: "msbuild, The Microsoft build tool for Visual Studio project solutions."
categories: "common"
---
> More information: <https://docs.microsoft.com/visualstudio/msbuild>.

- Build the first project file in the current directory:

```bash
msbuild
```

- Build a specific project file:

```bash
msbuild path/to/project_file
```

- Set one or more semicolon-separated targets to build:

```bash
msbuild path/to/project_file /target:targets
```

- Set one or more semicolon-separated properties:

```bash
msbuild path/to/project_file /property:name=value
```

- Set the build tools version to use:

```bash
msbuild path/to/project_file /toolsversion:version
```

- Display detailed information at the end of the log about how the project was configured:

```bash
msbuild path/to/project_file /detailedsummary
```

- Display detailed help information:

```bash
msbuild /help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | msbuild: add link to homepage | 2019-06-04T21:29:40 | [4a40b331080e](https://github.com/tldr-pages/tldr/commit/4a40b331080ee9255ab961a4a53c16294f5e80a5)
[Owen Voke](mailto:owzie123@gmail.com) | msbuild: add page (#2115) | 2018-05-19T13:15:41 | [2102852947eb](https://github.com/tldr-pages/tldr/commit/2102852947eb201c7b6440c5ef7fadc993f14780)

