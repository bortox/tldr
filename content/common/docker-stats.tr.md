---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker stats, TLDR Pages"
description: "docker stats, Konteynerler için kaynak kullanım istatistiklerinin canlı yayınını görüntüle."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/stats/>.

- Çalışan tüm konteynerlerin aynak kullanım istatistiklerinin canlı yayınını görüntüle:

```bash
docker stats
```

- Boşluk ile ayrılmış bir listedeki konteynerlerin canlı yayınını görüntüle:

```bash
docker stats container_ismi
```

- Konteyner'in CPU kullanım yüzdesini göstermek için sütun formatını değiştir:

```bash
docker stats --format ".Name:\t.CPUPerc"
```

- Tüm (çalışan veya durmuş) konteynerler için istatistikleri görüntüle:

```bash
docker stats --all
```

- İstatistikleri canlı yayınlamayı durdur ve yalnızca mevcut durumdaki istatistikleri görüntüle:

```bash
docker stats --no-stream
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

