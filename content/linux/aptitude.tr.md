---
author: ['Patrice Denis', 'lincc', 'Tan A']
date: 1643487459
title: "aptitude, TLDR Pages"
description: "aptitude, Debian ve Ubuntu paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Kullanılabilir paket ve sürüm listesini senkronize et. Bu, herhangi bir aptitude komutunu uygulamadan önce çalıştırılmalıdır:

```bash
aptitude update
```

- Yeni bir paket ve onun bağımlılıklarını kur:

```bash
aptitude install paket
```

- Paket ara:

```bash
aptitude search paket
```

- İndirilmiş bir paket ara: (`?installed` bir aptitude arama ifadesidir):

```bash
aptitude search '?installed(paket)'
```

- Bir paket ve onun bağımlılıklarını kaldır:

```bash
aptitude remove paket
```

- Yüklü paketleri son kullanılabilir sürümlerine yükselt:

```bash
aptitude upgrade
```

- Yüklü paketleri yükle (`aptitude upgrade` gibi), gereksizleri sil ve yeni bağımlılıkları karşılamak üzere ek paketler kur:

```bash
aptitude full-upgrade
```

- Bir paketin otomatik yükseltilmesini engellemek için onu beklemede tut:

```bash
aptitude hold '?installed(paket)'
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | aptitude: add Turkish translation (#4920) | 2020-11-01T20:20:12 | [ee142132237c](https://github.com/tldr-pages/tldr/commit/ee142132237cc4250ec686c2254c6528ebbd32b6)

