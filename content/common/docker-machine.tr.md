---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker-machine, TLDR Pages"
description: "docker-machine, Docker çalıştıran makineler oluştur ve onları yönet."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/machine/reference/>.

- Halihazırda çalışan docker makinelerini sırala:

```bash
docker-machine ls
```

- Belirli bir isim ile docker makinesi oluştur:

```bash
docker-machine create isim
```

- Bir makinenin durumunu öğren:

```bash
docker-machine status isim
```

- Bir makineyi başlat:

```bash
docker-machine start isim
```

- Bir makineyi durdur:

```bash
docker-machine stop isim
```

- Bir makine hakkındaki bilgileri incele:

```bash
docker-machine inspect isim
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

