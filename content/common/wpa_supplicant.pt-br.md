---
author: ['Marco Bonelli', 'lincc']
date: 1643487459
title: "wpa_supplicant"
description: "wpa_supplicant, Gerenciador de redes wireless protegidas."
categories: "common"
---
> Mais informações: <https://manned.org/wpa_supplicant.1>.

- Entrar em uma rede wireless protegida:

```bash
wpa_supplicant -i interface -c caminho/para/wpa_supplicant_conf.conf
```

- Entrar em uma rede wireless protegida e executar o wpa_cli em um daemon:

```bash
wpa_supplicant -B -i interface -c caminho/para/wpa_supplicant_conf.conf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

