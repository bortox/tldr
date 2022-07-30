---
author: ['Stig124', '7vikpeculiar', 'Ishaan Bhimwal', 'Starbeamrainbowlabs', 'Seth Falco']
date: 1658240132
title: "create_ap"
description: "create_ap, Create an AP (Access Point) at any channel."
categories: "linux"
---
> More information: <https://github.com/oblique/create_ap>.

- Create an open network with no passphrase:

```bash
create_ap wlan0 eth0 access_point_ssid
```

- Use a WPA + WPA2 passphrase:

```bash
create_ap wlan0 eth0 access_point_ssid passphrase
```

- Create an access point without Internet sharing:

```bash
create_ap -n wlan0 access_point_ssid passphrase
```

- Create a bridged network with Internet sharing:

```bash
create_ap -m bridge wlan0 eth0 access_point_ssid passphrase
```

- Create a bridged network with Internet sharing and a pre-configured bridge interface:

```bash
create_ap -m bridge wlan0 br0 access_point_ssid passphrase
```

- Create an access port for Internet sharing from the same Wi-Fi interface:

```bash
create_ap wlan0 wlan0 access_point_ssid passphrase
```

- Choose a different Wi-Fi adapter driver:

```bash
create_ap --driver wifi_adapter wlan0 eth0 access_point_ssid passphrase
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | create_ap: tweak casing (#2900) Follow-up to #2884 | 2019-04-15T02:15:07 | [7219be13ed27](https://github.com/tldr-pages/tldr/commit/7219be13ed2728b07cd445469bc108f5681c9318)
[7vikpeculiar](mailto:bugganasathviksanjeev1998@gmail.com) | create_ap: add page (#2884) | 2019-04-12T00:50:43 | [d879be8849ba](https://github.com/tldr-pages/tldr/commit/d879be8849ba60b316e38eb2f20b829f835671d6)

