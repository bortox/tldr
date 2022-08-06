---
author: ['vimalaguti', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1659669130
title: "hdparm"
description: "hdparm, Get and set SATA and IDE hard drive parameters."
categories: "linux"
---
> More information: <https://manned.org/hdparm>.

- Request the identification info of a given device:

```bash
sudo hdparm -I /dev/device
```

- Get the Advanced Power Management level:

```bash
sudo hdparm -B /dev/device
```

- Set the Advanced Power Management value (values 1-127 permit spin-down, and values 128-254 do not):

```bash
sudo hdparm -B 1 /dev/device
```

- Display the device's current power mode status:

```bash
sudo hdparm -C /dev/device
```

- Force a drive to immediately enter standby mode (usually causes a drive to spin down):

```bash
sudo hdparm -y /dev/device
```

- Put the drive into idle (low-power) mode, also setting its standby timeout:

```bash
sudo hdparm -S standby_timeout device
```

- Test the read speed of a specific device:

```bash
sudo hdparm -tT device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hdparm: add read speed example (#8302) | 2022-08-05T05:12:10 | [a25714f556dc](https://github.com/tldr-pages/tldr/commit/a25714f556dcf4232fc9eb976c40281f638574f0)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[vimalaguti](mailto:25081309+vimalaguti@users.noreply.github.com) | hdparm: add page (#3915) | 2020-03-23T07:33:18 | [3ae4f2c4012c](https://github.com/tldr-pages/tldr/commit/3ae4f2c4012c077f6cd0107e1be9a6a55da9fba1)

