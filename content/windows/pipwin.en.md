---
author: ['Erfan']
date: 1641098067
title: "pipwin, TLDR Pages"
description: "pipwin, A tool to install unofficial Python package binaries on Windows."
categories: "windows"
---
> More information: <https://github.com/lepisma/pipwin>.

- List all available packages for download:

```bash
pipwin list
```

- Search packages:

```bash
pipwin search partial_name|name
```

- Install a package:

```bash
pipwin install package_name
```

- Uninstall a package:

```bash
pipwin uninstall package_name
```

- Download a package to a specific directory:

```bash
pipwin download --dest path/to/directory package_name
```

- Install packages according to `requirements.txt`:

```bash
pipwin install --file path/to/requirements.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Erfan](mailto:41344995+flydeoo@users.noreply.github.com) | pipwin: add page (#7593) | 2022-01-02T05:34:27 | [4394c4fa0cec](https://github.com/tldr-pages/tldr/commit/4394c4fa0cec39ecf0d485d69f8822e1e988bc99)

