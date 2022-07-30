---
author: ['Emily Grace Seville']
date: 1647705698
title: "gacutil"
description: "gacutil, Global Assembly Cache (CAG) management utility."
categories: "common"
---
> More information: <https://manned.org/gacutil>.

- Install the specified assembly into GAC:

```bash
gacutil -i path/to/assembly.dll
```

- Uninstall the specified assembly from GAC:

```bash
gacutil -i assembly_display_name
```

- Print the content of GAC:

```bash
gacutil -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | gacutil: add page (#7898) * Add gacutil * Add the abbreviation to description Co-authored-by: Jakob Miksch <info@jakobmiksch.eu> * [...] | 2022-03-19T17:01:38 | [3eb4ea459a65](https://github.com/tldr-pages/tldr/commit/3eb4ea459a65f29222674aa0c647f4fe913c1a42)

