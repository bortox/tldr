---
author: ['Oğuz Ersen']
date: 1646865744
title: "ip rule, TLDR Pages"
description: "ip rule, IP yönlendirme politikası veri tabanı yönetimi."
categories: "linux"
---
> Daha fazla bilgi: <https://man7.org/linux/man-pages/man8/ip-rule.8.html>.

- Yönlendirme politikasını göster:

```bash
ip rule show|list
```

- Paket kaynak adreslerine dayalı yeni bir kural ekle:

```bash
sudo ip rule add from 192.168.178.2/32
```

- Paket hedef adreslerine dayalı yeni bir kural ekle:

```bash
sudo ip rule add to 192.168.178.2/32
```

- Paket kaynak adreslerine dayalı bir kuralı sil:

```bash
sudo ip rule delete from 192.168.178.2/32
```

- Paket hedef adreslerine dayalı bir kuralı sil:

```bash
sudo ip rule delete to 192.168.178.2/32
```

- Silinen tüm kuralları temizle:

```bash
ip rule flush
```

- Tüm kuralları bir dosyaya kaydet:

```bash
ip rule save > ip_kuralları.dat/dosyasının/yolu
```

- Tüm kuralları bir dosyadan geri yükle:

```bash
ip rule restore < ip_kuralları.dat/dosyasının/yolu
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip-rule: add Turkish translation | 2022-03-09T23:42:24 | [42831a9be8e8](https://github.com/tldr-pages/tldr/commit/42831a9be8e8461bf28eaa7bdd8fbf2192500d2c)

