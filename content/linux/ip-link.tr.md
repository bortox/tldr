---
author: ['Oğuz Ersen']
date: 1646865744
title: "ip link, TLDR Pages"
description: "ip link, Ağ arayüzlerini yönet."
categories: "linux"
---
> Daha fazla bilgi: <https://man7.org/linux/man-pages/man8/ip-link.8.html>.

- Tüm ağ arayüzleriyle ilgili bilgileri göster:

```bash
ip link
```

- Belirli bir ağ arayüzüyle ilgili bilgileri göster:

```bash
ip link show ethN
```

- Bir ağ arayüzünü etkinleştir veya devre dışı bırak:

```bash
ip link set ethN up|down
```

- Bir ağ arayüzüne anlamlı bir ad ver:

```bash
ip link set ethN alias "LAN Arayüzü"
```

- Bir ağ arayüzünün MAC adresini değiştir:

```bash
ip link set ethN address ff:ff:ff:ff:ff:ff
```

- Jumbo çerçeveleri kullanması için bir ağ arayüzünün MTU boyutunu değiştir:

```bash
ip link set ethN mtu 9000
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip-link: add Turkish translation | 2022-03-09T23:42:24 | [f2a5f1f4e2f1](https://github.com/tldr-pages/tldr/commit/f2a5f1f4e2f11e47f368405a8b977d9afc532219)

