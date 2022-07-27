---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git flow, TLDR Pages"
description: "git flow, Üst seviye depo işlemleri için Git uzantı koleksiyonu."
categories: "common"
---
> Daha fazla bilgi: <https://github.com/nvie/gitflow>.

- Varolan bir git deposu içinde başlat:

```bash
git flow init
```

- `develop` tabanlı bir özellik dalı üzerinde geliştirmeye başla:

```bash
git flow feature start özellik
```

- Özellik dalı üzerinde geliştirmeyi bitir, `develop` dalı ile birleştir ve dalı sil:

```bash
git flow feature finish özellik
```

- Özelliği uzak sunucuya yayınla:

```bash
git flow feature publish özellik
```

- Başka bir kullanıcı tarafından yayınlanan özelliği al:

```bash
git flow feature pull origin özellik
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)

