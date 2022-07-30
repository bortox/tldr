---
author: ['marchersimon', 'Seth Falco', 'Oğuz Ersen']
date: 1659075216
title: "nmcli connection, TLDR Pages"
description: "nmcli connection, NetworkManager ile bağlantı yönetimi."
categories: "linux"
---
> Daha fazla bilgi: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Tüm NetworkManager bağlantılarını listele (ad, UUID, tür ve aygıtı gösterir):

```bash
nmcli connection
```

- UUID belirterek bağlantıyı etkinleştir:

```bash
nmcli connection up uuid uuid
```

- Bağlantıyı devre dışı bırak:

```bash
nmcli connection down uuid uuid
```

- IPv4 ve IPv6 otomatik olarak yapılandırılan bir bağlantı oluştur:

```bash
nmcli connection add ifname arayüz_adı type ethernet ipv4.method auto ipv6.method auto
```

- Statik bir yalnızca IPv6 bağlantısı oluştur:

```bash
nmcli connection add ifname arayüz_adı type ethernet ip6 2001:db8::2/64 gw6 2001:db8::1 ipv6.dns 2001:db8::1 ipv4.method ignore
```

- Statik bir yalnızca IPv4 bağlantısı oluştur:

```bash
nmcli connection add ifname arayüz_adı type ethernet ip4 10.0.0.7/8 gw4 10.0.0.1 ipv4.dns 10.0.0.1 ipv6.method ignore
```

- Bir OVPN dosyasından OpenVPN kullanan bir VPN bağlantısı oluştur:

```bash
nmcli connection import type openvpn file vpn_yapılandırması.ovpn/dosyasının/yolu
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

