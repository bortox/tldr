---
author: ['Guido Lena Cota']
date: 1601580212
title: "git bundle, TLDR Pages"
description: "git bundle, Package objects and references into an archive."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-bundle>.

- Create a bundle file that contains all objects and references of a specific branch:

```bash
git bundle create path/to/file.bundle branch_name
```

- Create a bundle file of all branches:

```bash
git bundle create path/to/file.bundle --all
```

- Create a bundle file of the last 5 commits of the current branch:

```bash
git bundle create path/to/file.bundle -5 HEAD
```

- Create a bundle file of the latest 7 days:

```bash
git bundle create path/to/file.bundle --since=7.days HEAD
```

- Verify that a bundle file is valid and can be applied to the current repository:

```bash
git bundle verify path/to/file.bundle
```

- Print to the standard output the list of references contained in a bundle:

```bash
git bundle unbundle path/to/file.bundle
```

- Unbundle a specific branch from a bundle file into the current repository:

```bash
git pull path/to/file.bundle branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-bundle: add page (#4364) | 2020-10-01T21:23:32 | [3cdee951c5f3](https://github.com/tldr-pages/tldr/commit/3cdee951c5f347f4985a8d8b0d7a8c2983c29706)

