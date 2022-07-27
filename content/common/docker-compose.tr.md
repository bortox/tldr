---
author: ['Locour', 'lincc', 'Tan A']
date: 1643487459
title: "docker compose, TLDR Pages"
description: "docker compose, Çoklu konteynerli docker uygulamalarını çalıştırın ve yönetin."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/compose/reference/>.

- Tüm konteynerleri listele:

```bash
docker-compose ps
```

- Mevcut dizinde bir `docker-compose.yml` dosyası çalıştırarak arkaplandaki tüm konteynerleri çalıştırın ve başlatın:

```bash
docker-compose up -d
```

- Tüm konteynerleri çalıştırın ve gerekiyorsa yeniden oluşturun:

```bash
docker-compose up --build
```

- Tüm konteynerleri alternatif bir beste dosyasıyla başlatın:

```bash
docker-compose --file yoldan/dosyaya up
```

- Çalışan tüm konteynerleri durdurun:

```bash
docker-compose stop
```

- Tüm konteynerleri, ağları, imgeleri ve alanları durdurun ve silin:

```bash
docker-compose down --rmi all --volumes
```

- Tüm konteynerler için logları takip edin:

```bash
docker-compose logs --follow
```

- Belirtilmiş bir konteyner için logları takip edin:

```bash
docker-compose logs --follow konteyner_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker, docker-build, docker-compose: translate to Turkish (tr) (#5177) | 2021-01-28T18:48:22 | [814807414767](https://github.com/tldr-pages/tldr/commit/814807414767b7560cb28de03766adbda5c72f75)

