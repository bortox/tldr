---
author: ['Oğuz Ersen']
date: 1646490968
title: "nmcli, TLDR Pages"
description: "nmcli, NetworkManager'ı denetlemek için bir komut satırı aracı."
categories: "linux"
---
> `nmcli monitor` gibi bazı alt komutların kendi kullanım belgeleri vardır.

> Daha fazla bilgi: <https://manned.org/nmcli>.

- Bir `nmcli` alt komutunu çalıştır:

```bash
nmcli agent|connection|device|general|help|monitor|networking|radio komut_seçenekleri
```

- Kullanılan NetworkManager sürümünü görüntüle:

```bash
nmcli --version
```

- Yardımı görüntüle:

```bash
nmcli --help
```

- Bir alt komut için yardımı görüntüle:

```bash
nmcli alt_komut --help
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | nmcli*, nmtui, wpa*: add Turkish translation (#7850) * nmtui: add Turkish translation * nmcli: add Turkish translation * nmcli- [...] | 2022-03-05T15:36:08 | [45fa5e1372f0](https://github.com/tldr-pages/tldr/commit/45fa5e1372f0b34f97f4f57acd8ceb582cae961d)

