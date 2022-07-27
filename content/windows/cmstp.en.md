---
author: ['Lucas Gabriel Schneider', 'bl-ue', 'Owen Voke']
date: 1621541621
title: "cmstp, TLDR Pages"
description: "cmstp, A command-line tool for managing connection service profiles."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmstp>.

- Install a specific profile:

```bash
cmstp "path/to/profile"
```

- Install without creating a desktop shortcut:

```bash
cmstp /ns "path/to/profile"
```

- Install without checking for dependencies:

```bash
cmstp /nf "path/to/profile"
```

- Only install for the current user:

```bash
cmstp /su "path/to/profile"
```

- Install for all users (requires administrator privileges):

```bash
cmstp /au "path/to/profile"
```

- Install silently without any prompts:

```bash
cmstp /s "path/to/profile"
```

- Uninstall a specific profile:

```bash
cmstp /u "path/to/profile"
```

- Uninstall silently without a confirmation prompt:

```bash
cmstp /u /s "path/to/profile"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | cmstp: add page (#2675) | 2019-01-02T16:25:06 | [17f57489f111](https://github.com/tldr-pages/tldr/commit/17f57489f111d4dd479c077c2eb6281233e23b7a)

