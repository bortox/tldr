---
author: ['Oğuz Ersen']
date: 1646490968
title: "nmcli device, TLDR Pages"
description: "nmcli device, NetworkManager ile donanım aygıtı yönetimi."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/nmcli.1>.

- Tüm ağ arayüzlerinin durumlarını yazdır:

```bash
nmcli device status
```

- Kullanılabilir kablosuz erişim noktalarını yazdır:

```bash
nmcli device wifi
```

- Belirtilen ad ve parola ile kablosuz ağa bağlan:

```bash
nmcli device wifi connect ssid password parola
```

- Geçerli kablosuz ağ için parola ve QR kodunu yazdır:

```bash
nmcli device wifi show-password
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

