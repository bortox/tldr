---
author: ['Oğuz Ersen']
date: 1646490968
title: "nmtui, TLDR Pages"
description: "nmtui, NetworkManager'ı denetlemek için metin tabanlı kullanıcı arayüzü."
categories: "linux"
---
> Gezinmek için ok tuşlarını, seçmek için Enter tuşunu kullanın.

> Daha fazla bilgi: <https://networkmanager.dev/docs/api/latest/nmtui.html>.

- Kullanıcı arayüzünü aç:

```bash
nmtui
```

- Etkinleştirme veya devre dışı bırakma seçeneğiyle birlikte kullanılabilir bağlantıların bir listesini göster:

```bash
nmtui connect
```

- Belirtilen ağa bağlan:

```bash
nmtui connect ad|uuid|aygıt|SSID
```

- Belirtilen ağı düzenle/ekle/sil:

```bash
nmtui edit ad|kimlik
```

- Sistem ana makine adını ayarla:

```bash
nmtui hostname
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

