---
author: ['Pierre Rudloff', 'Axel Navarro', 'marchersimon']
date: 1625253777
title: "dexdump, TLDR Pages"
description: "dexdump, Display information about Android DEX files."
categories: "common"
---
> More information: <https://manned.org/dexdump>.

- Extract classes and methods from an APK file:

```bash
dexdump path/to/file.apk
```

- Display header information of DEX files contained in an APK file:

```bash
dexdump -f path/to/file.apk
```

- Display the dis-assembled output of executable sections:

```bash
dexdump -d path/to/file.apk
```

- Output results to a file:

```bash
dexdump -o path/to/file path/to/file.apk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Axel Navarro](mailto:navarroaxel@gmail.com) | dexdump: add more information link (#5142) | 2021-01-15T18:24:33 | [b112894a976a](https://github.com/tldr-pages/tldr/commit/b112894a976a301565f4784165376e14585fa740)
[Pierre Rudloff](mailto:contact@rudloff.pro) | dexdump: add page (#3563) | 2019-11-16T07:32:26 | [b0f9ecfdb874](https://github.com/tldr-pages/tldr/commit/b0f9ecfdb87402fe48516b09396c5b2a3364583a)

