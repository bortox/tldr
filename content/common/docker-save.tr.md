---
author: ['Tan A', 'lincc']
date: 1643487459
title: "docker save"
description: "docker save, Bir veya daha fazla docker imgesini arşivlemek için dışa aktar."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/save/>.

- Bir imgeyi, stdout'u tar arşivine yönlendirerek kaydet:

```bash
docker save imge:etiket > {örnek/dosya.tar
```

- Bir imgeyi, bir tar arşivine kaydet:

```bash
docker save --output örnek/dosya.tar imge:etiket
```

- Bir imgenin tüm etiketlerini kaydet:

```bash
docker save --output örnek/dosya.tar imge_ismi
```

- Bir imgenin belirli etiketlerini kaydetmek için elle seç:

```bash
docker save --output örnek/dosya.tar imge_ismi:etiket1 imge_ismi:etiket2 ...
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

