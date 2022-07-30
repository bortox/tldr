---
author: ['Mateusz Soszyński', 'kai', 'Patrice Denis']
date: 1657535784
title: "deluser"
description: "deluser, Delete a user from the system."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/adduser/deluser.html>.

- Remove a user:

```bash
sudo deluser username
```

- Remove a user and their home directory:

```bash
sudo deluser --remove-home username
```

- Remove a user and their home, but backup their files into a `.tar.gz` file in the specified directory:

```bash
sudo deluser --backup-to path/to/backup_directory --remove-home username
```

- Remove a user, and all files owned by them:

```bash
sudo deluser --remove-all-files username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kai](mailto:gmdezreal@gmail.com) | deluser: prefix examples with sudo (#8174) | 2022-07-11T12:36:24 | [057f52541c54](https://github.com/tldr-pages/tldr/commit/057f52541c54b0ab2a25dc3dc5185fd7fab3142c)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | deluser, userdel: add page (#5245) | 2021-02-07T20:05:03 | [7dcdcea28c3c](https://github.com/tldr-pages/tldr/commit/7dcdcea28c3c47f411c9611ee1827f8dc83ad938)

