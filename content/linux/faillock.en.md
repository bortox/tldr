---
author: ['Martin Matous']
date: 1649897347
title: "faillock, TLDR Pages"
description: "faillock, Display and modify authentication failure record files."
categories: "linux"
---
> More information: <https://manned.org/faillock>.

- List login failures of all users:

```bash
sudo faillock
```

- List login failures of the specified user:

```bash
sudo faillock --user user
```

- Reset the failure records of the specified user:

```bash
sudo faillock --user user --reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Martin Matous](mailto:18654729+mmatous@users.noreply.github.com) | faillock: add page (#7971) Signed-off-by: Martin Matous <m@matous.dev> Co-authored-by: CleanMachine1 [...] | 2022-04-14T02:49:07 | [3ce3531cb046](https://github.com/tldr-pages/tldr/commit/3ce3531cb0466c350d2f5c6057d61fa348ffe0f5)

