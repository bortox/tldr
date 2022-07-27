---
author: ['marchersimon']
date: 1631529949
title: "tlmgr info, TLDR Pages"
description: "tlmgr info, Show information about TeX Live packages."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all available TeX Live packages, prefexing installed ones with `i`:

```bash
tlmgr info
```

- List all available collections:

```bash
tlmgr info collections
```

- List all available schemes:

```bash
tlmgr info scheme
```

- Show information about a specific package:

```bash
tlmgr info package_name
```

- List all files contained in a specific package:

```bash
tlmgr info package_name --list
```

- List all installed packages:

```bash
tlmgr info --only-installed
```

- Show only specific information about a package:

```bash
tlmgr info package_name --data "name,category,installed,size,depends,..."
```

- Print all available packages as JSON encoded array:

```bash
tlmgr info --json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-info: add page (#6511) | 2021-09-13T12:45:49 | [e347e43cb989](https://github.com/tldr-pages/tldr/commit/e347e43cb9899e3dac802e82821f9f99a068efca)

