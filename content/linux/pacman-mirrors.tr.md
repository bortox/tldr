---
author: ['Tan A', 'lincc']
date: 1643487459
title: "pacman-mirrors"
description: "pacman-mirrors, Manjaro Linux için pacman aynalistesi oluşturucu."
categories: "linux"
---
> pacman-mirrors'ın çalıştırıldığı her vakit, E`sudo pacman -Syyu` komutu ile veritabanının senkronize edilmesi ve sistemin güncellenmesi gerekir.

> Daha fazla bilgi: <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Varsayılan ayarlar ile bir aynalistesi oluştur:

```bash
sudo pacman-mirrors --fasttrack
```

- Mevcut aynaların durumunu göster:

```bash
pacman-mirrors --status
```

- Mevcut dalı göster:

```bash
pacman-mirrors --get-branch
```

- Farklı bir dala geç:

```bash
sudo pacman-mirrors --api --set-branch stabil|instabil|test_ediliyor
```

- Sadece IP adresinin bulunduğu ülkenin aynalarını kullanarak bir aynalistesi oluştur:

```bash
sudo pacman-mirrors --geoip
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

