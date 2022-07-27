---
author: ['Ruben Vereecken', 'lord63', 'Gubolin', 'Emily Grace Seville']
date: 1647882468
title: "wpa_cli, TLDR Pages"
description: "wpa_cli, Add and configure wlan interfaces."
categories: "linux"
---
> More information: <https://manned.org/wpa_cli>.

- Scan for available networks:

```bash
wpa_cli scan
```

- Show scan results:

```bash
wpa_cli scan_results
```

- Add a network:

```bash
wpa_cli add_network number
```

- Set a network's SSID:

```bash
wpa_cli set_network number ssid "SSID"
```

- Enable network:

```bash
wpa_cli enable_network number
```

- Save config:

```bash
wpa_cli save_config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reworked wpa_cli to adhere to one-example rule | 2016-01-24T16:58:52 | [61d03c4fdfa8](https://github.com/tldr-pages/tldr/commit/61d03c4fdfa8c6599b01f31757587e152d6654c6)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[Gubolin](mailto:gubolin@fantasymail.de) | add wpa_cli | 2014-03-09T18:49:01 | [f81fffbe1cac](https://github.com/tldr-pages/tldr/commit/f81fffbe1cac015d8de228d7eb46d782d7b8a959)

