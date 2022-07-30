---
author: ['marchersimon']
date: 1616956214
title: "pio update"
description: "pio update, Update installed PlatformIO Core packages, development platforms and global libraries."
categories: "common"
---
> See also: `pio platform update`, `pio lib update`.

> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_update.html>.

- Perform a full update of all packages, development platforms and global libraries:

```bash
pio update
```

- Update core packages only (skips platforms and libraries):

```bash
pio update --core-packages
```

- Check for new versions of packages, platforms and libraries but do not actually update them:

```bash
pio update --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-update: add page (#5520) | 2021-03-28T20:30:14 | [1727939a29ec](https://github.com/tldr-pages/tldr/commit/1727939a29ec14c53e62092a339f06712cf0adab)

