---
author: ['marchersimon', 'lincc', 'Tan A']
date: 1643487459
title: "docker system, TLDR Pages"
description: "docker system, Docker verilerini yönet ve sistem bilgisi görüntüle."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/system/>.

- Yardım göster:

```bash
docker system
```

- Docker disk kullanımını göster:

```bash
docker system df
```

- Disk kullanımı üzerine detaylı bilgi göster:

```bash
docker system df --verbose
```

- Kullanılmayan veriyi sil:

```bash
docker system prune
```

- Kullanılmayan ve geçmişte birden çok kez oluşturulan veriyi sil:

```bash
docker system prune --filter="until=saathdakikam"
```

- Docker deamon'dan tam-zamanlı eylemleri görüntüle:

```bash
docker system events
```

- Geçerli JSON satırları olarak yayınlanan konteynerleden tam-zamanlı eylemleri göster:

```bash
docker system events --filter 'type=container' --format 'json .'
```

- Sistem bilgisi göster:

```bash
docker system info
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

