---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker logs"
description: "docker logs, Konteyner kaydını yazdırır."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/logs>.

- Bir konteyner içindeki kayıtları yazdır:

```bash
docker logs konteyner_ismi
```

- Kayıtları yazdır ve izle:

```bash
docker logs -f konteyner_ismi
```

- Son 5 kaydı yazdır:

```bash
docker logs konteyner_ismi --tail 5
```

- Kayıtları yazdır ve zaman damgaları ile iliştir:

```bash
docker logs -t konteyner_ismi
```

- Belli bir konteyner çalışma zamanındaki (i.e. 23m, 10s, 2013-01-02T13:23:37) kayıtları yazdır:

```bash
docker logs konteyner_ismi --until zaman
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

