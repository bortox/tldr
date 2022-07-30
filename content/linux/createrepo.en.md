---
author: ['Jeremy Heckt']
date: 1645254973
title: "createrepo"
description: "createrepo, Initializes an RPM repository in the given directory, including all XML and SQLite files."
categories: "linux"
---
> More information: <https://manned.org/createrepo>.

- Initialize a basic repository in a directory:

```bash
createrepo path/to/directory
```

- Initialize a repository, exclude test RPMs and display verbose logs:

```bash
createrepo -v -x test_*.rpm path/to/directory
```

- Initialize a repository, using SHA1 as the checksum algorithm, and ignoring symbolic links:

```bash
createrepo -S -s sha1 path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jeremy Heckt](mailto:turnipsoup@users.noreply.github.com) | createrepo: add page (#7789) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: CleanMachine1 [...] | 2022-02-19T08:16:13 | [b645de29cd6b](https://github.com/tldr-pages/tldr/commit/b645de29cd6bc4036414de23ad23958f51ff13d8)

