---
author: ['pxgamer', 'Rafael Julio', 'Gustavo Dias Alexandre', 'Maharaj Fawwaz A. Yusran']
date: 1634730630
title: "fastboot, TLDR Pages"
description: "fastboot, Communicate with connected Android devices when in bootloader mode (the one place `adb` doesn't work)."
categories: "common"
---
> More information: <https://cs.android.com/android/platform/superproject/+/master:system/core/fastboot>.

- Unlock the bootloader:

```bash
fastboot oem unlock
```

- Relock the bootloader:

```bash
fastboot oem lock
```

- Reboot the device from fastboot mode into fastboot mode again:

```bash
fastboot reboot bootloader
```

- Flash a given image:

```bash
fastboot flash file.img
```

- Flash a custom recovery image:

```bash
fastboot flash recovery file.img
```

- Display connected devices:

```bash
fastboot devices
```

- Display all information of a device:

```bash
fastboot getvar all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | bugreport, bugreportz, fastboot: use links to code search (#7074) | 2021-10-20T13:50:30 | [e48d44f376dd](https://github.com/tldr-pages/tldr/commit/e48d44f376dd7610f183ca3d490fe9adfcf3e518)
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)
[Gustavo Dias Alexandre](mailto:gfdiasa@gmail.com) | fastboot: add getvar example (#4312) | 2020-09-03T22:09:49 | [8371c62ba9a5](https://github.com/tldr-pages/tldr/commit/8371c62ba9a553bb2fb1d6f6265dae3ea1fecc6e)
[pxgamer](mailto:owzie123@gmail.com) | fastboot: add link to homepage | 2019-06-07T23:58:59 | [5ce612337509](https://github.com/tldr-pages/tldr/commit/5ce6123375090dab745787e0124c4ada02231e36)
[Maharaj Fawwaz A. Yusran](mailto:faww4zintelgent4@gmail.com) | fastboot: add page (#1856) | 2018-01-07T19:42:22 | [ed3334f04867](https://github.com/tldr-pages/tldr/commit/ed3334f04867b5ac98dc6813e8720bc9fe10c044)

