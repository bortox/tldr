---
author: ['Axel Navarro']
date: 1642131234
title: "xdg-user-dirs-update, TLDR Pages"
description: "xdg-user-dirs-update, Update XDG user directories."
categories: "linux"
---
> More information: <https://manned.org/xdg-user-dirs-update>.

- Change XDG's DESKTOP directory to the specified directory (must be absolute):

```bash
xdg-user-dirs-update --set DESKTOP "path/to/directory"
```

- Write the result to the specified dry-run-file instead of the `user-dirs.dirs` file:

```bash
xdg-user-dirs-update --dummy-output "path/to/dry_run_file" --set xdg_user_directory "path/to/directory"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)

