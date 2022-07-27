---
author: ['marchersimon', 'Jan T. Sott']
date: 1623093754
title: "iscc, TLDR Pages"
description: "iscc, Compiler for Inno Setup installers."
categories: "windows"
---
> It compiles an Inno Setup scripts into an Windows installer executable.

> More information: <https://jrsoftware.org/isinfo.php>.

- Compile an Inno Setup script:

```bash
iscc path/to/file.iss
```

- Quietly compile an Inno Setup installer:

```bash
iscc /Q path/to/file.iss
```

- Compile a signed Inno Setup installer:

```bash
iscc /S=name=command path/to/file.iss
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | windows: add links | 2021-06-07T21:22:34 | [4755d715b788](https://github.com/tldr-pages/tldr/commit/4755d715b788004b3c86bf0266eee49d19d79d52)
[Jan T. Sott](mailto:jan@idleberg.com) | iscc: add page (#2224) | 2018-07-31T21:32:05 | [26bdd7c49d09](https://github.com/tldr-pages/tldr/commit/26bdd7c49d0939d81d71624fa603336b2d284402)

