---
author: ['Axel Navarro']
date: 1614292298
title: "kreadconfig5"
description: "kreadconfig5, Read KConfig entries for KDE Plasma."
categories: "linux"
---
> More information: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Read a key from the global configuration:

```bash
kreadconfig5 --group group_name --key key_name
```

- Read a key from a specific configuration file:

```bash
kwriteconfig5 --file path/to/file --group group_name --key key_name
```

- Check if systemd is used to start the Plasma session:

```bash
kreadconfig5 --file startkderc --group General --key systemdBoot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | kreadconfig5: add page (#5293) | 2021-02-25T23:31:38 | [c2eeae45cca2](https://github.com/tldr-pages/tldr/commit/c2eeae45cca28ab36381245e7bd9e1d2ca099b89)

