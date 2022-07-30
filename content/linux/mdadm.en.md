---
author: ['Agniva De Sarker', 'sebastientinel', 'Like-all', 'Ruben Vereecken', 'marchersimon', 'lord63']
date: 1618584134
title: "mdadm"
description: "mdadm, RAID management utility."
categories: "linux"
---
> More information: <https://manned.org/mdadm>.

- Create array:

```bash
mdadm --create /dev/md/MyRAID --level raid_level --raid-devices number_of_disks /dev/sdXN
```

- Stop array:

```bash
mdadm --stop /dev/md0
```

- Mark disk as failed:

```bash
mdadm --fail /dev/md0 /dev/sdXN
```

- Remove disk:

```bash
mdadm --remove /dev/md0 /dev/sdXN
```

- Add disk to array:

```bash
mdadm --assemble /dev/md0 /dev/sdXN
```

- Show RAID info:

```bash
mdadm --detail /dev/md0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[Like-all](mailto:like-all@yandex.com) | mdadm: mistype fix | 2014-08-25T12:50:27 | [786e90e86414](https://github.com/tldr-pages/tldr/commit/786e90e86414587cdc62fe42675009b4f973da33)
[Like-all](mailto:like-all@yandex.com) | mdadm - RAID management utility | 2014-08-04T05:31:06 | [f39674eeef4e](https://github.com/tldr-pages/tldr/commit/f39674eeef4e5f172a4794aa4c8261c4fbae57c2)

