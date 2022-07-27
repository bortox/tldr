---
author: ['marchersimon', 'lincc', 'Tan A']
date: 1643487459
title: "docker exec, TLDR Pages"
description: "docker exec, Halihazırda çalışan bir Docker konteyneri üstünde komut çalıştır."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/exec/>.

- Halihazırda çalışan bir konteynerin üstünde interaktif bir kabuk oturumunu çalıştır:

```bash
docker exec --interactive --tty konteyner_ismi /bin/bash
```

- Halihazırda çalışan bir konteynerin üstüne arkaplanda çalışmak üzere (ayrılmış) bir komut çalıştır:

```bash
docker exec --detach konteyner_ismi komut
```

- Belirtilen bir komutu üstünde çalıştırmak adına çalışan dizini seç:

```bash
docker exec --interactive -tty --workdir örnek/dizin konteyner_ismi komut
```

- Varolan konteyner üstünde arkaplanda çalışmak üzere bir komut çalıştır ancak stdin'i açık tut:

```bash
docker exec --interactive --detach konteyner_ismi komut
```

- Çalışmakta olan bir bash oturumu içinde bir çevre değişkeni belirle:

```bash
docker exec --interactive --tty --env değişken_ismi=value konteyner_ismi /bin/bash
```

- Belirtilmiş bir kullanıcı olarak komut çalıştır:

```bash
docker exec --user kullanıcı konteyner_ismi komut
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

