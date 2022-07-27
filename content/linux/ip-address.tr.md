---
author: ['Oğuz Ersen']
date: 1646865744
title: "ip address, TLDR Pages"
description: "ip address, IP adresi yönetimi alt komutu."
categories: "linux"
---
> Daha fazla bilgi: <https://manned.org/ip-address>.

- Ağ arayüzlerini ve ilişkili IP adreslerini listele:

```bash
ip address
```

- Yalnızca etkin ağ arayüzlerini gösterecek şekilde filtrele:

```bash
ip address show up
```

- Belirli bir ağ arayüzü hakkındaki bilgileri görüntüle:

```bash
ip address show dev eth0
```

- Bir ağ arayüzüne bir IP adresi ekle:

```bash
ip address add ip_adresi dev eth0
```

- Bir ağ arayüzünden bir IP adresini kaldır:

```bash
ip address delete ip_adresi dev eth0
```

- Belirli bir kapsamdaki tüm IP adreslerini bir ağ arayüzünden sil:

```bash
ip address flush dev eth0 scope global|host|link
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip-address: add Turkish translation | 2022-03-09T23:42:24 | [2ce0394878a9](https://github.com/tldr-pages/tldr/commit/2ce0394878a957b6764ed340c402f30800d9dfa6)

