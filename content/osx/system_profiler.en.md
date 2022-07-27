---
author: ['Ruben Vereecken', 'meowmeowcat', 'rprieto', 'Emily Grace Seville']
date: 1644837703
title: "system_profiler, TLDR Pages"
description: "system_profiler, Report system hardware and software configuration."
categories: "osx"
---
> More information: <https://ss64.com/osx/system_profiler.html>.

- Display a full system profiler report which can be opened by System Profiler.app:

```bash
system_profiler -xml > MyReport.spx
```

- Display a hardware overview (Model, CPU, Memory, Serial, etc):

```bash
system_profiler SPHardwareDataType
```

- Print the system serial number:

```bash
system_profiler SPHardwareDataType|grep "Serial Number (system)" | awk '{ print $4 }'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

