---
author: ['Ethan Kinnear']
date: 1655050076
title: "eget, TLDR Pages"
description: "eget, Easily install prebuilt binaries from GitHub."
categories: "common"
---
> More information: <https://github.com/zyedidia/eget>.

- Download a prebuilt binary for the current system from a repository on GitHub:

```bash
eget zyedidia/micro
```

- Download from a URL:

```bash
eget https://go.dev/dl/go1.17.5.linux-amd64.tar.gz
```

- Specify the location to place the downloaded files:

```bash
eget zyedidia/micro --to=path/to/directory
```

- Specify a `git` tag instead of using the latest version:

```bash
eget zyedidia/micro --tag=v2.0.10
```

- Install the latest pre-release instead of the latest stable version:

```bash
eget zyedidia/micro --pre-release
```

- Only download the asset, skipping extraction:

```bash
eget zyedidia/micro --download-only
```

- Only download if there is a newer release then the currently downloaded version:

```bash
eget zyedidia/micro --upgrade-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ethan Kinnear](mailto:contact@superatomic.dev) | eget: add page (#8122) | 2022-06-12T18:07:56 | [75b303618bf4](https://github.com/tldr-pages/tldr/commit/75b303618bf4259fc177f5a53135367e4132dd21)

