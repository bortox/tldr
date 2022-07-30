---
author: ['Waldir Pimenta', 'Stig124', 'Austin', 'Michael Pearce']
date: 1625841955
title: "edquota"
description: "edquota, Edit quotas for a user or group. By default it operates on all filesystems with quotas."
categories: "linux"
---
> Quota information is stored permanently in the `quota.user` and `quota.group` files in the root of the filesystem.

> More information: <https://manned.org/edquota>.

- Edit quota of the current user:

```bash
edquota --user $(whoami)
```

- Edit quota of a specific user:

```bash
sudo edquota --user username
```

- Edit quota for a group:

```bash
sudo edquota --group group
```

- Restrict operations to a given filesystem (by default edquota operates on all filesystems with quotas):

```bash
sudo edquota --file-system filesystem
```

- Edit the default grace period:

```bash
sudo edquota -t
```

- Duplicate a quota to other users:

```bash
sudo edquota -p reference_user destination_user1 destination_user2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | edquota: minor tweaks to commands and descriptions (#1113) | 2016-10-16T15:57:23 | [9bef52067061](https://github.com/tldr-pages/tldr/commit/9bef52067061d2326c59f77d04e7399894501905)
[Michael Pearce](mailto:pogomaniac@hotmail.com) | edquota: add page (#1001) | 2016-10-13T08:48:16 | [7681e7fa89a8](https://github.com/tldr-pages/tldr/commit/7681e7fa89a870151a2ad4bdf4be12f4a24b5017)

