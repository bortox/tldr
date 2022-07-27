---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git rev-list, TLDR Pages"
description: "git rev-list, Değişiklikleri (commit'leri) ters kronolojik sırada sırala."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-rev-list>.

- Mevcut daldaki tüm commit'leri sırala:

```bash
git rev-list HEAD
```

- Belirtilen daldaki belirtilen tarihten daha yakın olan commit'leri sırala:

```bash
git rev-list --since='2019-12-01 00:00:00' dal_ismi
```

- Belirtilen commit'deki tüm birleştirme commit'lerini sırala:

```bash
git rev-list --merges commit
```

- Belirtilen etiketten itibaren olan commit sayılarını çıkar:

```bash
git rev-list tag_name..HEAD --count
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

