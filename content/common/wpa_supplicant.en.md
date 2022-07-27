---
author: ['Brian Choromanski', 'Victorien ELVINGER']
date: 1634674282
title: "wpa_supplicant, TLDR Pages"
description: "wpa_supplicant, Manage protected wireless networks."
categories: "common"
---
> More information: <https://manned.org/wpa_supplicant.1>.

- Join a protected wireless network:

```bash
wpa_supplicant -i interface -c path/to/wpa_supplicant_conf.conf
```

- Join a protected wireless network and run it in a daemon:

```bash
wpa_supplicant -B -i interface -c path/to/wpa_supplicant_conf.conf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Brian Choromanski](mailto:BrianChoromanski@gmail.com) | auditd, sftp, time, umount, unzip, w, which, wpa_supplicant: add link (#7037) | 2021-10-19T22:11:22 | [7f29e1695f3a](https://github.com/tldr-pages/tldr/commit/7f29e1695f3a3e3a2ecc20c730b8484a59daa588)
[Victorien ELVINGER](mailto:Conaclos@users.noreply.github.com) | wpa_supplicant: add page (#2290) | 2018-10-16T01:04:52 | [15c3f9ec7ad3](https://github.com/tldr-pages/tldr/commit/15c3f9ec7ad3b09e2caea212a5dd05882660b5f2)

