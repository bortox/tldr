---
author: ['dz-at-tc']
date: 1634801906
title: "fossil commit"
description: "fossil commit, Commit files to a Fossil repository."
categories: "linux"
---
> More information: <https://fossil-scm.org/home/help/commit>.

- Create a new version containing all the changes in the current checkout; user will be prompted for a comment:

```bash
fossil commit
```

- Create a new version containing all the changes in the current checkout, using the specified comment:

```bash
fossil commit --comment "comment"
```

- Create a new version containing all the changes in the current checkout with a comment read from a specific file:

```bash
fossil commit --message-file path/to/commit_message_file
```

- Create a new version containing changes from the specified files; user will be prompted for a comment:

```bash
fossil commit path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dz-at-tc](mailto:49352191+dz-at-tc@users.noreply.github.com) | fossil-commit: add page (#7051) | 2021-10-21T09:38:26 | [aa3bb7b0e802](https://github.com/tldr-pages/tldr/commit/aa3bb7b0e802ea7d286e81dcfed3b1093876e1d9)

