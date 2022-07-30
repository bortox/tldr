---
author: ['Emily Grace Seville', 'rprieto', 'pixel', 'Guido Lena Cota', 'Ruben Vereecken']
date: 1644837703
title: "networksetup"
description: "networksetup, Configuration tool for Network System Preferences."
categories: "osx"
---
> More information: <https://support.apple.com/guide/remote-desktop/about-networksetup-apdd0c5a2d5/mac>.

- List available network service providers (Ethernet, Wi-Fi, Bluetooth, etc):

```bash
networksetup -listallnetworkservices
```

- Show network settings for a particular networking device:

```bash
networksetup -getinfo "Wi-Fi"
```

- Get currently connected Wi-Fi network name (Wi-Fi device usually en0 or en1):

```bash
networksetup -getairportnetwork en0
```

- Connect to a particular Wi-Fi network:

```bash
networksetup -setairportnetwork en0 Airport Network SSID password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[pixel](mailto:chrissx@chrissx.de) | networksetup, port, xcode-select, xcodebuild: add more information links (#7754) * port: more info * xcodebuild: more info * xcode- [...] | 2022-02-14T04:43:29 | [4e2c525e311a](https://github.com/tldr-pages/tldr/commit/4e2c525e311a327155c32b467b5ff24b8df22318)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

