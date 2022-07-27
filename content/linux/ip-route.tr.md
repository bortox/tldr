---
author: ['Oğuz Ersen']
date: 1646865744
title: "ip route, TLDR Pages"
description: "ip route, IP yönlendirme tablosu yönetimi alt komutu."
categories: "linux"
---
> Daha fazla bilgi: <https://manned.org/ip-route>.

- Yönlendirme tablosunu görüntüle:

```bash
ip route show|list
```

- Ağ geçidini kullanan öntanımlı bir yönlendirme ekle:

```bash
sudo ip route add default via ağ_geçidi_ip_adresi
```

- `eth0` arayüzünü kullanan öntanımlı bir yönlendirme ekle:

```bash
sudo ip route add default dev eth0
```

- Statik bir yönlendirme ekle:

```bash
sudo ip route add hedef_ip_adresi via ağ_geçidi_ip_adresi dev eth0
```

- Statik bir yönlendirmeyi sil:

```bash
sudo ip route del hedef_ip_adresi dev eth0
```

- Statik bir yönlendirmeyi değiştir:

```bash
sudo ip route change|replace hedef_ip_adresi via ağ_geçidi_ip_adresi dev eth0
```

- Bir IP adresine ulaşmak için çekirdek tarafından hangi yönlendirmenin kullanılacağını göster:

```bash
ip route get hedef_ip_adresi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip-route: add Turkish translation | 2022-03-09T23:42:24 | [34d72cabc8eb](https://github.com/tldr-pages/tldr/commit/34d72cabc8eb1a6af4711792da74e05d485b2e5f)

