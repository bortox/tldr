---
author: ['marchersimon', 'slash3b', 'Balázs Úr', 'Sailesh Shrestha', 'kai']
date: 1658921926
title: "visudo, TLDR Pages"
description: "visudo, Safely edit the sudoers file."
categories: "common"
---
> More information: <https://www.sudo.ws/docs/man/visudo.man>.

- Edit the sudoers file:

```bash
sudo visudo
```

- Check the sudoers file for errors:

```bash
sudo visudo -c
```

- Edit the sudoers file using a specific editor:

```bash
sudo EDITOR=editor visudo
```

- Display version information:

```bash
visudo --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: add/edit more information link (#8255) | 2022-07-27T13:38:46 | [df1c9855a704](https://github.com/tldr-pages/tldr/commit/df1c9855a704f1360748c4b7652f8bca1db3a6c7)
[kai](mailto:gmdezreal@gmail.com) | visudo: add example (#8154) | 2022-06-27T12:17:40 | [6ae6a1bad285](https://github.com/tldr-pages/tldr/commit/6ae6a1bad2855d7f65c085ea964e4d9651fe74fc)
[Sailesh Shrestha](mailto:34860977+werewolf-65@users.noreply.github.com) | sdcv, visudo: add link and --version example (#7207) | 2021-11-25T22:32:48 | [61c0ac06d84f](https://github.com/tldr-pages/tldr/commit/61c0ac06d84fa1984a72793c04ff5017df99c802)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[slash3b](mailto:slash3b@gmail.com) | getent command was added | 2016-02-21T15:23:08 | [5de5f06ffb64](https://github.com/tldr-pages/tldr/commit/5de5f06ffb644b3cd35846127e571a007030ae80)
[slash3b](mailto:slash3b@gmail.com) | visudo command added | 2016-02-20T00:09:13 | [777cb8c67d1a](https://github.com/tldr-pages/tldr/commit/777cb8c67d1ae7deb031da174981489a1ff3e1be)

