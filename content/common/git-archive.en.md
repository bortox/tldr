---
author: ['Guido Lena Cota']
date: 1601464703
title: "git archive, TLDR Pages"
description: "git archive, Create an archive of files from a named tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-archive>.

- Create a tar archive from the contents of the current HEAD and print it to standard output:

```bash
git archive --verbose HEAD
```

- Create a zip archive from the current HEAD and print it to standard output:

```bash
git archive --verbose --format=zip HEAD
```

- Same as above, but write the zip archive to file:

```bash
git archive --verbose --output=path/to/file.zip HEAD
```

- Create a tar archive from the contents of the latest commit on a specific branch:

```bash
git archive --output=path/to/file.tar branch_name
```

- Create a tar archive from the contents of a specific directory:

```bash
git archive --output=path/to/file.tar HEAD:path/to/directory
```

- Prepend a path to each file to archive it inside a specific directory:

```bash
git archive --output=path/to/file.tar --prefix=path/to/prepend/ HEAD
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-archive: add page (#4362) | 2020-09-30T13:18:23 | [7c681eea51f5](https://github.com/tldr-pages/tldr/commit/7c681eea51f59c42391e0eacd3f4d91f19552bd7)

