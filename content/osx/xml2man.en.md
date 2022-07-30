---
author: ['pixel']
date: 1648417778
title: "xml2man"
description: "xml2man, Compile MPGL to mdoc."
categories: "osx"
---
> More information: <https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/HeaderDoc/mpgl/mpgl.html>.

- Compile an MPGL file to a viewable man page:

```bash
xml2man path/to/command.mxml
```

- Compile an MPGL file to a specific output file:

```bash
xml2man path/to/service.mxml path/to/service.7
```

- Compile an MPGL file to a specific output file, overwriting if it already exists:

```bash
xml2man -f path/to/function.mxml path/to/function.3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | sdef, xml2man: add page (#7927) | 2022-03-27T23:49:38 | [0bc72f549695](https://github.com/tldr-pages/tldr/commit/0bc72f549695d557ccf1f659f45321687f65fd71)

