---
author: ['Patrice Denis', 'bl-ue', 'lincc', 'Tan A']
date: 1643487459
title: "apt-get, TLDR Pages"
description: "apt-get, Debian ve Ubuntu paket yönetim aracı."
categories: "linux"
---
> Paket aramak için `apt-cache` komutunu kullanın.

> Daha fazla bilgi: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Kullanılabilir paket ve versiyon listesini güncelleyin (diğer `apt-get` komutlarını çalıştırmadan önce kullanmanız önerilir):

```bash
apt-get update
```

- Bir paket yükleyin veya son sürüme güncelleyin:

```bash
apt-get install paket
```

- Bir paketi silin:

```bash
apt-get remove paket
```

- Bir paketi ve konfigürasyon dosyalarını silin:

```bash
apt-get purge paket
```

- Yüklü paketlerin hepsini son sürümlerine yükseltin:

```bash
apt-get upgrade
```

- Yerel depoyu temizleyin - kullanılmayan gereksiz paket dosyalarını (.deb) silin:

```bash
apt-get autoclean
```

- Artık gerekmeyen paketleri silin:

```bash
apt-get autoremove
```

- Yüklenmiş paketleri yükseltin (`upgrade` gibi), ancak gereksiz paketleri silin ve yeni bağımlılıkları memnun edecek ek paketler kurun:

```bash
apt-get dist-upgrade
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | apt-get: add Turkish translation (#4917) | 2020-11-01T15:54:32 | [41b69bd45b64](https://github.com/tldr-pages/tldr/commit/41b69bd45b64a3f4503d39e06d8d4e5e6f2b9d05)

