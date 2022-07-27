---
author: ['lincc', 'Tan A']
date: 1643487459
title: "gitlab, TLDR Pages"
description: "gitlab, GitLab API'si için Ruby sarıcı ve CLI aracı."
categories: "common"
---
> `gitlab ctl` gibi bazı alt komutların kendi kullanım kılavuzları vardır.

> Daha fazla bilgi: <https://narkoz.github.io/gitlab/>.

- Yeni bir proje oluştur:

```bash
gitlab create_project proje_ismi
```

- Belirtilen commit ile ilgili bilgi al:

```bash
gitlab commit proje_ismi commit_değeri
```

- Bit CI pipeline'ındaki işler ile ilgili bilgi al:

```bash
gitlab pipeline_jobs proje_ismi pipeline_id'si
```

- Belirtilen CI işini başlat:

```bash
gitlab job_play proje_ismi iş_id'si
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)

