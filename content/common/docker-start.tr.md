---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker start, TLDR Pages"
description: "docker start, Bir veya daha fazla durmuş konteyneri başlar."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/start/>.

- Yardım göster:

```bash
docker start
```

- Bir docker konteynerini başlat:

```bash
docker start konteyner
```

- Bir konteyneri, ona stdout ile stderr'i ekleyerek ve sinyaller göndererek başlat:

```bash
docker start --attach konteyner
```

- Bir veya daha fazla boşlukla ayrılarak belirtilmiş konteynerleri başlar:

```bash
docker start konteyner(ler)
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

