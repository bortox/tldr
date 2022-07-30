---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker ps"
description: "docker ps, Docker konteynerlerini sırala."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/ps/>.

- Halihazırda çalışan docker konteynerlerini listele:

```bash
docker ps
```

- Tüm (durmuş veya çalışan) docker konteynerlerini listele:

```bash
docker ps --all
```

- En son oluşturulan (durmuş veya çalışan) konteynerleri listele:

```bash
docker ps --latest
```

- İsimlerinde belirtilen dizeleri içeren konteynerleri filtrele:

```bash
docker ps --filter="name=isim"
```

- Belirtilen imge ile akrabalık taşıyan konteynerleri filtrele:

```bash
docker ps --filter "ancestor=imge:tag"
```

- Konteynerleri çıkış durum koduna göre filtrele:

```bash
docker ps --all --filter="exited=kod"
```

- Konteynerleri mevcut durumlarına (oluşturulma, çalışma, silinme, durma, çıkma ve ölme) göre sırala:

```bash
docker ps --filter="status=mevcut_durum"
```

- Belirtilmiş bir hacmi gömen veya belirtilmiş bir yola gömülmüş hacmi içeren konteynerleri filtrele:

```bash
docker ps --filter="volume=örnek/dizin" --format "table .ID\t.Image\t.Names\t.Mounts"
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

