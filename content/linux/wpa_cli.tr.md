---
author: ['Oğuz Ersen', 'marchersimon']
date: 1659075216
title: "wpa_cli"
description: "wpa_cli, Kablosuz LAN arayüzleri ekleyin ve yapılandırın."
categories: "linux"
---
> Daha fazla bilgi: <https://manned.org/wpa_cli>.

- Kullanılabilir ağları tara:

```bash
wpa_cli scan
```

- Tarama sonuçlarını göster:

```bash
wpa_cli scan_results
```

- Ağ ekle:

```bash
wpa_cli add_network numara
```

- Bir ağın SSID değerini ayarla:

```bash
wpa_cli set_network numara ssid "SSID"
```

- Ağı etkinleştir:

```bash
wpa_cli enable_network numara
```

- Yapılandırmayı kaydet:

```bash
wpa_cli save_config
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

