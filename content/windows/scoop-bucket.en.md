---
author: ['Lukas']
date: 1602285511
title: "scoop bucket"
description: "scoop bucket, Manage buckets: Git repositories containing files which describe how scoop installs applications."
categories: "windows"
---
> If Scoop doesn't know where the bucket is located its repository location must be specified.

> More information: <https://github.com/lukesampson/scoop/wiki/Buckets>.

- List all buckets currently in use:

```bash
scoop bucket list
```

- List all known buckets:

```bash
scoop bucket known
```

- Add a known bucket by its name:

```bash
scoop bucket add name
```

- Add an unknown bucket by its name and Git repository URL:

```bash
scoop bucket add name https://example.com/repository.git
```

- Remove a bucket by its name:

```bash
scoop bucket rm name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lukas](mailto:LukBukkit@users.noreply.github.com) | scoop-bucket: add page (#4554) | 2020-10-10T01:18:31 | [583653c7014f](https://github.com/tldr-pages/tldr/commit/583653c7014f93be4fb047fe834baf424b0a1504)

