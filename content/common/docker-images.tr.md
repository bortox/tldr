---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker images, TLDR Pages"
description: "docker images, Docker imgelerini yönet."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/images/>.

- Tüm Docker imgelerini listele:

```bash
docker images
```

- Orta düzeyler de dahil olmak üzere tüm Docker imgelerini sırala:

```bash
docker images --all
```

- Çıktıyı sessiz modda (yalnızca sayısal ID'ler olarak) sırala:

```bash
docker images --quiet
```

- Herhangi bir konteyner tarafından kullanılmayan tüm Docker imgelerini sırala:

```bash
docker images --filter dangling=true
```

- İsminde belirtilen dizeleri taşıyan imgeleri sırala:

```bash
docker images "*isim*"
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

