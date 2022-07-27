---
author: ['Seth Falco']
date: 1622931822
title: "flatpak-builder, TLDR Pages"
description: "flatpak-builder, Help build application dependencies."
categories: "linux"
---
> More information: <https://docs.flatpak.org/en/latest/flatpak-builder-command-reference.html>.

- Build a Flatpak and export it to a new repository:

```bash
flatpak-builder path/to/build_directory path/to/manifest
```

- Build a Flatpak and export it to the specified repository:

```bash
flatpak-builder --repo=repository_name path/to/build_directory path/to/manifest
```

- Build a Flatpak and install it locally:

```bash
flatpak-builder --install path/to/build_directory path/to/manifest
```

- Build and sign a Flatpak and export it to the specified repository:

```bash
flatpak-builder --gpg-sign=key_id --repo=repository_name path/to/manifest
```

- Run a shell inside of an application sandbox without installing it:

```bash
flatpak-builder --run path/to/build_directory path/to/manifest sh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | flatpak-builder: add page (#6089) | 2021-06-06T00:23:42 | [0a5e38a2c037](https://github.com/tldr-pages/tldr/commit/0a5e38a2c037fad68bd3c23ff0860bf1834e90dd)

