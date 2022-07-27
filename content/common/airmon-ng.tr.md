---
author: ['kupasout']
date: 1635464853
title: "airmon-ng, TLDR Pages"
description: "airmon-ng, Kablosuz ağ cihazlarında izleme modunu etkinleştirin."
categories: "common"
---
> Daha fazla bilgi: <https://www.aircrack-ng.org/doku.php?id=airmon-ng>.

- Kablosuz cihazları ve durumlarını listeleyin:

```bash
sudo airmon-ng
```

- Belirli bir cihaz için izleme modunu açın:

```bash
sudo airmon-ng start wlan0
```

- Kablosuz cihazları kullanan rahatsız edici işlemleri sonlandırın:

```bash
sudo airmon-ng check kill
```

- Belirli bir ağ arabirimi için izleme modunu kapatın:

```bash
sudo airmon-ng stop wlan0mon
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[kupasout](mailto:63257976+kupasout@users.noreply.github.com) | airmon-ng: add Turkish translation (#7261) | 2021-10-29T01:47:33 | [1c7a8ead844f](https://github.com/tldr-pages/tldr/commit/1c7a8ead844f6e9aa1643af514c54b07d4300a12)

