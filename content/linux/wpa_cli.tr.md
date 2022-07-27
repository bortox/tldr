---
author: ['Oğuz Ersen']
date: 1646490968
title: "wpa_cli, TLDR Pages"
description: "wpa_cli, Kablosuz LAN arayüzleri ekleyin ve yapılandırın."
categories: "linux"
---
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
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

