---
author: ['marchersimon', 'Oğuz Ersen']
date: 1659075216
title: "nmcli device, TLDR Pages"
description: "nmcli device, NetworkManager ile donanım aygıtı yönetimi."
categories: "linux"
---
> Daha fazla bilgi: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

