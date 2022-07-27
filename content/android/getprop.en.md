---
author: ['Seth Falco', 'marchersimon']
date: 1629050349
title: "getprop, TLDR Pages"
description: "getprop, Show information about Android system properties."
categories: "android"
---
> More information: <https://manned.org/getprop>.

- Display information about Android system properties:

```bash
getprop
```

- Display information about a specific property:

```bash
getprop prop
```

- Display the SDK API level:

```bash
getprop ro.build.version.sdk
```

- Display the Android version:

```bash
getprop ro.build.version.release
```

- Display the Android device model:

```bash
getprop ro.vendor.product.model
```

- Display the OEM unlock status:

```bash
getprop ro.oem_unlock_supported
```

- Display the MAC address of the Android's Wi-Fi card:

```bash
getprop ro.boot.wifimacaddr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: fix command descriptions (#5807) | 2021-04-22T22:09:21 | [4b891616c6a1](https://github.com/tldr-pages/tldr/commit/4b891616c6a1f21e836b56d216b7ec008e1dd746)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | getprop: change more information link (#5686) | 2021-04-04T19:08:42 | [43ce314f3e27](https://github.com/tldr-pages/tldr/commit/43ce314f3e2734d86bc140e552ce76f8f1731b00)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | getprop: add page (#5456) | 2021-04-04T00:08:41 | [59308e5928b5](https://github.com/tldr-pages/tldr/commit/59308e5928b525e8684c02796d6cf18598df51af)

