---
author: ['Mehmet Mallı', 'lincc', 'Tan A']
date: 1643487459
title: "docker, TLDR Pages"
description: "docker, Docker konteyner ve imgelerini yönetir."
categories: "common"
---
> `docker run` gibi bazı alt komutların kendi dökümantasyonu bulunmaktadır.

> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Şuan çalışan docker konteynerlerini listele:

```bash
docker ps
```

- Tüm (çalışan veya duran) docker konteynerlerini listele:

```bash
docker ps -a
```

- Bir imgeden özel bir isimle konteyner başlat:

```bash
docker run --name konteyner_ismi imge
```

- Varolan bir konteyneri başlat veya durdur:

```bash
docker start|stop konteyner_ismi
```

- Bir docker kaydından imge çek:

```bash
docker pull imge
```

- Halihazırda çalışan bir konteyner içinde komut istemcisi aç:

```bash
docker exec -it konteyner_ismi sh
```

- Durmuş bir konteyneri sil:

```bash
docker rm konteyner_ismi
```

- Bir konteynerin kaydını çek ve takip et:

```bash
docker logs -f konteyner_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Mehmet Mallı](mailto:mallimehmet@gmail.com) | docker: add Turkish translation for subcommand text (#6792) | 2021-10-04T22:13:01 | [b50bfe513e9c](https://github.com/tldr-pages/tldr/commit/b50bfe513e9c85ed7e97a7f9e442bbe46e902360)
[Mehmet Mallı](mailto:mallimehmet@gmail.com) | docker, docker-run: fix Turkish translation (#6776) | 2021-10-04T14:16:26 | [0a12712baf45](https://github.com/tldr-pages/tldr/commit/0a12712baf45f08177eabfbdb741034151bab7ea)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker, docker-build, docker-compose: translate to Turkish (tr) (#5177) | 2021-01-28T18:48:22 | [814807414767](https://github.com/tldr-pages/tldr/commit/814807414767b7560cb28de03766adbda5c72f75)

