---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker service"
description: "docker service, Bir docker daemon'unun üzerindeki servisleri yönet."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/service/>.

- Bir docker daeomon'unun üzerindeki servisleri listele:

```bash
docker service ls
```

- Yeni bir servis yarat:

```bash
docker service create --name servis_ismi imge:etiket
```

- Boşluk ile ayrılmış bir servis listesinin detaylı bilgisini görüntüle:

```bash
docker service inspect servis_ismi|ID
```

- Boşluk ile ayrılmış bir servis listesinin görevlerini sırala:

```bash
docker service ps servis_ismi|ID
```

- Boşluk ile ayrılmış bir servis listesi için belirli bir replika miktarına yüksel:

```bash
docker service scale servis_ismi=replika_miktarı
```

- Boşluk ile ayrılmış bir servis listesini sil:

```bash
docker service rm servis_ismi|ID
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

