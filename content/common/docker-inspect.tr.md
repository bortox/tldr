---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker inspect"
description: "docker inspect, Docker objelerinde bulunan düşük seviye bilgiyi gösterir."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/inspect/>.

- Yardım içeriğini göster:

```bash
docker inspect
```

- Bir konteyner, imge veya hacim ile ilgili bilgiyi ismini veya ID'sini girerek görüntüle:

```bash
docker inspect konteyner|imge|ID
```

- Bir konteynerin IP adresini görüntüle:

```bash
docker inspect --format='range .NetworkSettings.Networks.IPAddressend' konteyner
```

- Konteynerin log dosyasının yolunu görüntüle:

```bash
docker inspect --format='.LogPath' konteyner
```

- Konteynerin imge ismini görüntüle:

```bash
docker inspect --format='.Config.Image' konteyner
```

- Konfigürasyon bilgisini JSON olarak görüntüle:

```bash
docker inspect --format='json .Config' konteyner
```

- Tüm port limanlayıcıları görüntüle:

```bash
docker inspect --format='range $p, $conf := .NetworkSettings.Ports $p -> (index $conf 0).HostPort end' konteyner
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

