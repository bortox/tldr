---
author: ['Jonas']
date: 1610306105
title: "svn changelist, TLDR Pages"
description: "svn changelist, Associate a changelist with a set of files."
categories: "common"
---
> More information: <http://svnbook.red-bean.com/en/1.7/svn.advanced.changelists.html>.

- Add files to a changelist, creating the changelist if it does not exist:

```bash
svn changelist changelist_name path/to/file1 path/to/file2
```

- Remove files from a changelist:

```bash
svn changelist --remove path/to/file1 path/to/file2
```

- Remove the whole changelist at once:

```bash
svn changelist --remove --recursive --changelist changelist_name .
```

- Add the contents of a space-separated list of directories to a changelist:

```bash
svn changelist --recursive changelist_name path/to/directory1 path/to/directory2
```

- Commit a changelist:

```bash
svn commit --changelist changelist_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonas](mailto:jonas.schulz.12@gmail.com) | svn-changelist: add page (#5118) | 2021-01-10T20:15:05 | [aaae44875fec](https://github.com/tldr-pages/tldr/commit/aaae44875fec514c0b02f242a0d831a6299aa186)

