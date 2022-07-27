---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker build, TLDR Pages"
description: "docker build, Bir Dockerfile'dan imge yaratın."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/build/>.

- Mevcut dizindeki Dockerfile'dan bir docker imgesi oluşturun:

```bash
docker build .
```

- Belirtilen URL'deki Dockerfile'dan bir docker imgesi oluşturun:

```bash
docker build ornekadres.com/ornek-dizin/ornek-docker-projesi
```

- Bir docker imgesi oluşturun ve etiketleyin:

```bash
docker build --tag isim:etiket .
```

- İmge oluştururken çerez kullanımını etkisizleştirin:

```bash
docker build --no-cache --tag isim:etiket .
```

- Belirtilen Dockerfile ile bir docker imgesi oluşturun:

```bash
docker build --file Dockerfile .
```

- Kişiselleştirilmiş yapım-zaman değerleriyle oluşturun:

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker, docker-build, docker-compose: translate to Turkish (tr) (#5177) | 2021-01-28T18:48:22 | [814807414767](https://github.com/tldr-pages/tldr/commit/814807414767b7560cb28de03766adbda5c72f75)

