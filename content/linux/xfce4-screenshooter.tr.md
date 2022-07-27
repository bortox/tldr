---
author: ['marchersimon', 'lincc', 'Tan A']
date: 1643487459
title: "xfce4-screenshooter, TLDR Pages"
description: "xfce4-screenshooter, XFCE4 ekran görüntüsü aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://docs.xfce.org/apps/xfce4-screenshooter/start>.

- Ekran görüntüsü alma grafik arayüzünü başlat:

```bash
xfce4-screenshooter
```

- Tüm ekranın ekran görüntüsünü al ve nasıl devam edileceğini belirlemek adına grafik arayüzünü başlat:

```bash
xfce4-screenshooter --fullscreen
```

- Tüm ekranın ekran görüntüsünü al ve görüntüyü belirtilen dizine kaydet:

```bash
xfce4-screenshooter --fullscreen --save örnek/dizin
```

- Ekran görüntüsünü çekmeden önce belli bir süre bekle:

```bash
xfce4-screenshooter --delay saniye_miktarı
```

- Ekranın (fare ile seçilecek) belli bir bölümünün görüntüsünü al:

```bash
xfce4-screenshooter --region
```

- Üzerinde bulunulan pencerenin görüntüsünü al ve panoya kopyala:

```bash
xfce4-screenshooter --window --clipboard
```

- Üzerinde bulunulan pencerenin görüntüsünü qal ve seçilen bir program ile aç:

```bash
xfce4-screenshooter --window --open gimp
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xfce4-screenshooter, xfce4-terminal: add link (#6075) | 2021-05-31T19:06:30 | [cfd0b5bd34da](https://github.com/tldr-pages/tldr/commit/cfd0b5bd34da972d7780b0b8580b3fb2af145607)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | xfce-*: add Turkish translation (#5333) | 2021-03-02T12:15:22 | [80f0fbb2ba01](https://github.com/tldr-pages/tldr/commit/80f0fbb2ba01e63ad3ea3a07bdaa45647f12f53d)

