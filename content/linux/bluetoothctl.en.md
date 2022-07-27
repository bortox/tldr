---
author: ['Seth Falco', 'Stig124', 'Matthias Langhard', 'Axel Navarro', 'marchersimon']
date: 1643827401
title: "bluetoothctl, TLDR Pages"
description: "bluetoothctl, Manage Bluetooth devices from the command-line."
categories: "linux"
---
> More information: <https://bitbucket.org/serkanp/bluetoothctl>.

- Enter the `bluetoothctl` shell:

```bash
bluetoothctl
```

- List all known devices:

```bash
bluetoothctl devices
```

- Power the Bluetooth controller on or off:

```bash
bluetoothctl power on|off
```

- Pair with a device:

```bash
bluetoothctl pair mac_address
```

- Remove a device:

```bash
bluetoothctl remove mac_address
```

- Connect to a paired device:

```bash
bluetoothctl connect mac_address
```

- Disconnect from a paired device:

```bash
bluetoothctl disconnect mac_address
```

- Display help:

```bash
bluetoothctl help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | bluetoothctl: add power and help examples (#7387) | 2021-11-10T23:42:48 | [a77ff935a41e](https://github.com/tldr-pages/tldr/commit/a77ff935a41e21801a128c2ae3a5afc40dcbb08e)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Matthias Langhard](mailto:matthias@langhard.com) | bluetoothctl: add page (#3590) | 2019-11-19T13:01:22 | [a002465004ed](https://github.com/tldr-pages/tldr/commit/a002465004edca7720e7bc7571d9716c2f8f3538)

