---
author: ['marchersimon']
date: 1659360764
title: "tlmgr conf"
description: "tlmgr conf, Manage the TeX Live configuration."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Show the current TeX Live configuration:

```bash
tlmgr conf
```

- Show the current `texmf`, `tlmgr`, or `updmap` configuration:

```bash
tlmgr conf texmf|tlmgr|updmap
```

- Show only a specific configuration option:

```bash
tlmgr conf texmf|tlmgr|updmap configuration_key
```

- Set a specific configuration option:

```bash
tlmgr conf texmf|tlmgr|updmap configuration_key value
```

- Delete a specific configuration option:

```bash
tlmgr conf texmf|tlmgr|updmap --delete configuration_key
```

- Disable the execution of system calls via `\write18`:

```bash
tlmgr conf texmf shell_escape 0
```

- Show all additional `texmf` trees:

```bash
tlmgr conf auxtrees show
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-conf: add page (#8188) | 2022-08-01T15:32:44 | [f1792178bdbe](https://github.com/tldr-pages/tldr/commit/f1792178bdbe4d0c3c101d06ac8981c13ea92e65)

