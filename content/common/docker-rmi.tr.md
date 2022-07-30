---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker rmi"
description: "docker rmi, Bir veya daha fazla Docker imgesini sil."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/rmi/>.

- Yardım göster:

```bash
docker rmi
```

- Bir veya daha fazla imgeyi isimlerini belirterek sil:

```bash
docker rmi imge1 imge2 ...
```

- Bir imgeyi zorla sil:

```bash
docker rmi --force imge
```

- Bir imgeyi etiketlenmemiş ana yollarını silmeden sil:

```bash
docker rmi --no-prune imge
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

