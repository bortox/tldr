---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1612112718
title: "csc"
description: "csc, The Microsoft C# Compiler."
categories: "common"
---
> More information: <https://docs.microsoft.com/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe>.

- Compile one or more C# files to a CIL executable:

```bash
csc path/to/input_file_a.cs path/to/input_file_b.cs
```

- Specify the output filename:

```bash
csc /out:path/to/filename path/to/input_file.cs
```

- Compile into a `.dll` library instead of an executable:

```bash
csc /target:library path/to/input_file.cs
```

- Reference another assembly:

```bash
csc /reference:path/to/library.dll path/to/input_file.cs
```

- Embed a resource:

```bash
csc /resource:path/to/resource_file path/to/input_file.cs
```

- Automatically generate XML documentation:

```bash
csc /doc:path/to/output.xml path/to/input_file.cs
```

- Specify an icon:

```bash
csc /win32icon:path/to/icon.ico path/to/input_file.cs
```

- Strongly-name the resulting assembly with a keyfile:

```bash
csc /keyfile:path/to/keyfile path/to/input_file.cs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | csc: add link to homepage | 2019-06-09T18:53:49 | [616f7d3ec5a4](https://github.com/tldr-pages/tldr/commit/616f7d3ec5a41f1177632890413f33ebd6a09c69)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | csc: clarify example. (#2940) | 2019-04-23T15:04:25 | [9c59940f45fd](https://github.com/tldr-pages/tldr/commit/9c59940f45fd5371b190c2f170425d789a742cbb)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | csc: add page (#2557) | 2018-11-07T07:14:54 | [ef0ff7fbf55c](https://github.com/tldr-pages/tldr/commit/ef0ff7fbf55c0f03fdee24cc81bef7b708185da6)

