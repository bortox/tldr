---
author: ['marchersimon', 'Mehmet Mallı', 'lincc', 'Tan A']
date: 1643487459
title: "docker run, TLDR Pages"
description: "docker run, Yeni bir Docker konteynerinde bir komut çalıştır."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/run/>.

- Yeni bir konteynerde, etiketlenmiş bir imgeden komut çalıştır:

```bash
docker run imge:etiket komut
```

- Yeni bir konteynerde arkaplanda çalışacak şekilde komut çalıştır ve ID'sini göster:

```bash
docker run -d imge komut
```

- İnteraktif mod ve pseudo-TTY'deki bir açık-kapalı konteynerde komut çalıştır:

```bash
docker run --rm -it imge komut
```

- Yeni bir konteynerde geçebilmiş çevresel değişkenler ile komut çalıştır:

```bash
docker run -e 'değişken=değer' -e değişken imge komut
```

- Yeni bir konteynerde bağlama takılı hacimlerle komut çalıştır:

```bash
docker run -v örnek/host:örnek/konteyner imge komut
```

- Yayınlanmış portları içeren yeni bir konteynerde komut çalıştır:

```bash
docker run -p host_portu:konteyner_portu imge komut
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Mehmet Mallı](mailto:mallimehmet@gmail.com) | docker, docker-run: fix Turkish translation (#6776) | 2021-10-04T14:16:26 | [0a12712baf45](https://github.com/tldr-pages/tldr/commit/0a12712baf45f08177eabfbdb741034151bab7ea)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

