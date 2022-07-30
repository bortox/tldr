---
author: ['Lucas Gabriel Schneider', 'kmyounes', 'z7y8hsBP']
date: 1629110041
title: "losetup"
description: "losetup, Set up and control loop devices."
categories: "linux"
---
> More information: <https://manned.org/losetup>.

- List loop devices with detailed info:

```bash
losetup -a
```

- Attach a file to a given loop device:

```bash
sudo losetup /dev/loop /path/to/file
```

- Attach a file to a new free loop device and scan the device for partitions:

```bash
sudo losetup --show --partscan -f /path/to/file
```

- Attach a file to a read-only loop device:

```bash
sudo losetup --read-only /dev/loop /path/to/file
```

- Detach all loop devices:

```bash
sudo losetup -D
```

- Detach a given loop device:

```bash
sudo losetup -d /dev/loop
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[z7y8hsBP](mailto:51470766+z7y8hsBP@users.noreply.github.com) | losetup: change order (#3839) | 2020-02-05T19:22:17 | [a4d4c805dd4a](https://github.com/tldr-pages/tldr/commit/a4d4c805dd4ac984539c031cc0eec75441831eb0)
[z7y8hsBP](mailto:51470766+z7y8hsBP@users.noreply.github.com) | losetup: added example for --read-only and --partscan (#3792) | 2020-01-24T22:40:35 | [b80fdb65d8a5](https://github.com/tldr-pages/tldr/commit/b80fdb65d8a5fc038fd5813b063de085cf70b700)
[kmyounes](mailto:kmyounes@protonmail.com) | losetup: add page (#1415) | 2017-06-25T21:41:09 | [18b2c9564667](https://github.com/tldr-pages/tldr/commit/18b2c95646672aa39f217ef99fcb97809fdcb2c5)

