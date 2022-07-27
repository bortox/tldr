---
author: ['marchersimon', 'aurum77', 'lincc']
date: 1643487459
title: "xrandr, TLDR Pages"
description: "xrandr, Bir ekran için boyut, yön ve/veya çıkış yansımasını ayarla."
categories: "linux"
---
> Daha fazla bilgi: <https://www.x.org/releases/current/doc/man/man1/xrandr.1.xhtml>.

- Sistemin mevcut durumunu göster (bilinen ekranlar, çözünürlükler, ...):

```bash
xrandr --query
```

- Bağlantısı kesilmiş çıkışları devre dışı bırak ve bağlanmış olanları varsayılan ayarlar ile devreye sok:

```bash
xrandr --auto
```

- DisplayPort 1'in çözünürlük ve yenileme hızını 1920x1080, 60Hz olarak değiştir:

```bash
xrandr --output DP1 --mode 1920x1080 --rate 60
```

- HDMI2'nin çözünürlüğünü 1280x1024'e değiştirip, DP1'in sağına koy:

```bash
xrandr --output HDMI2 --mode 1280x1024 --right-of DP1
```

- VGA1 çıkışını devre dışı bırak:

```bash
xrandr --output VGA1 --off
```

- LVDS1 için parlaklığı 50% yap:

```bash
xrandr --output LVDS1 --brightness 0.5
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xrandr: remove duplicate example (#7389) | 2021-11-08T17:48:32 | [8793761d559f](https://github.com/tldr-pages/tldr/commit/8793761d559fedf3cb9f1a58705cbd044cba4cde)
[aurum77](mailto:58880138+aurum77@users.noreply.github.com) | xrandr: add Turkish translation (#7191) | 2021-10-27T20:34:09 | [cd38b90e3be0](https://github.com/tldr-pages/tldr/commit/cd38b90e3be0af731ea88f91724c4f6c84c5ddfe)

