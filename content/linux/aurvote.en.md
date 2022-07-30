---
author: ['marchersimon']
date: 1629726391
title: "aurvote"
description: "aurvote, Vote for packages in the Arch User Repository."
categories: "linux"
---
> To be able to vote, the file `~/.config/aurvote` must exist and contain your AUR credentials.

> More information: <https://github.com/archlinuxfr/aurvote>.

- Interactively create the file `~/.config/aurvote` containing your AUR username and password:

```bash
aurvote --configure
```

- Vote for one or more AUR packages:

```bash
aurvote package1 package2 ...
```

- Unvote one or more AUR packages:

```bash
aurvote --unvote package1 package2 ...
```

- Check if one or more AUR packages have already been voted:

```bash
aurvote --check package1 package2 ...
```

- Show help for `aurvote`:

```bash
aurvote --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | aurvote: add page (#6394) * aurvote: add page | 2021-08-23T15:46:31 | [6904f29a907f](https://github.com/tldr-pages/tldr/commit/6904f29a907f611decbe959b43b19393fef05c9a)

