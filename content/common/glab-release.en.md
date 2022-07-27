---
author: ['Reinhart Previano Koentjoro']
date: 1642567138
title: "glab release, TLDR Pages"
description: "glab release, Manage GitLab releases from the command-line."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/release>.

- List releases in a Gitlab repository, limited to 30 items:

```bash
glab release list
```

- Display information about a specific release:

```bash
glab release view tag
```

- Create a new release:

```bash
glab release create tag
```

- Delete a specific release:

```bash
glab release delete tag
```

- Download assets from a specific release:

```bash
glab release download tag
```

- Upload assets to a specific release:

```bash
glab release upload tag path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-release: add page (#7643) | 2022-01-19T05:38:58 | [3762d44bb2e2](https://github.com/tldr-pages/tldr/commit/3762d44bb2e260835837438577b8ec0cf6924063)

