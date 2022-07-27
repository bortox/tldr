---
author: ['marchersimon']
date: 1633362251
title: "tlmgr check, TLDR Pages"
description: "tlmgr check, Check the consistency of a TeX Live installation."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Check the consistency of the whole TeX Live installation:

```bash
tlmgr check all
```

- Check the consistency of the whole TeX Live information in verbose mode:

```bash
tlmgr check all -v
```

- Check for missing dependencies:

```bash
tlmgr check depends
```

- Check if all TeX Live executables are present:

```bash
tlmgr check executes
```

- Check if all files listed in the local TLPDB are present:

```bash
tlmgr check files
```

- Check for duplicate filenames in the runfiles sections:

```bash
tlmgr check runfiles
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-check: add page (#6586) | 2021-10-04T17:44:11 | [2d26897c713e](https://github.com/tldr-pages/tldr/commit/2d26897c713ee881051b9ae4cfe1061a7ad5cb22)

