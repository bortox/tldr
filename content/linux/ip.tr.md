---
author: ['Oğuz Ersen']
date: 1646865744
title: "ip"
description: "ip, Yönlendirmeyi, aygıtları, kural yönlendirmesini ve tünelleri görüntüle / değiştir."
categories: "linux"
---
> `ip address` gibi bazı alt komutların kendi kullanım belgeleri vardır.

> Daha fazla bilgi: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- Arayüzlerin bilgilerini ayrıntılı bir şekilde listele:

```bash
ip address
```

- Arayüzlerin ağ katmanı bilgilerini kısa bir şekilde listele:

```bash
ip -brief address
```

- Arayüzlerin bağlantı katmanı bilgilerini kısa bir şekilde listele:

```bash
ip -brief link
```

- Yönlendirme tablosunu görüntüle:

```bash
ip route
```

- Komşuları (ARP tablosunu) göster:

```bash
ip neighbour
```

- Bir arayüzü etkinleştir/devre dışı bırak:

```bash
ip link set arayüz up/down
```

- Bir arayüze IP adresi ekle/sil:

```bash
ip addr add/del ip/maske dev arayüz
```

- Öntanımlı yönlendirme ekle:

```bash
ip route add default via ip dev arayüz
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip: add Turkish translation | 2022-03-09T23:42:24 | [bf61b04d0068](https://github.com/tldr-pages/tldr/commit/bf61b04d0068cdef4b233c7574f9a95d9f05578c)

