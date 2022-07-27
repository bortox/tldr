---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git push, TLDR Pages"
description: "git push, Commit'leri uzak depoya yolla."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-push>.

- Mevcut daldaki yerel değişiklikleri onun uzak eşine gönder:

```bash
git push
```

- Belirtilen daldaki yerel değişiklikleri onun uzak eşine gönder:

```bash
git push uzak_bağlantı yerel_dal
```

- Mevcut dalı bir uzak dal ismi ayarlayarak uzak depoda yayınla:

```bash
git push uzak_bağlantı -u uzak_dal
```

- Yerel dallardaki tüm değişiklikleri onların belirtilen uzak depodaki uzak eşlerine gönder:

```bash
git push --all uzak_bağlantı
```

- Uzak depodaki bir dalı sil:

```bash
git push uzak_bağlantı --delete uzak_dal
```

- Yerel eşi olmayan uzak dalları sil:

```bash
git push --prune uzak_bağlantı
```

- Daha yzak depoda olmayan etiketleri yayınla:

```bash
git push --tags
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

