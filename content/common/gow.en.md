---
author: ['Michael Cale']
date: 1645780685
title: "gow, TLDR Pages"
description: "gow, Watches Go files and restarts the app on changes."
categories: "common"
---
> More information: <https://github.com/mitranim/gow>.

- Start and watch the current directory:

```bash
gow run .
```

- Start the application with the specified arguments:

```bash
gow run . argument1 argument2 ...
```

- Watch subdirectories in verbose mode:

```bash
gow -v -w=path/to/directory1,path/to/directory2,... run .
```

- Watch the specified file extensions:

```bash
gow -e=go,html run .
```

- Display help:

```bash
gow -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michael Cale](mailto:michaelcale@users.noreply.github.com) | gow: add page (#7805) | 2022-02-25T10:18:05 | [afca7adc24b0](https://github.com/tldr-pages/tldr/commit/afca7adc24b05826106900c9e5aa0f3f1b4150f2)

