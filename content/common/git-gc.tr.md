---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git gc, TLDR Pages"
description: "git gc, Gereksiz dosyaları silerek yerel depoyu optimize et."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-gc>.

- Depoyu optimize et:

```bash
git gc
```

- Agresifçe optimiize et (daha uzun sürer):

```bash
git gc --aggressive
```

- Gevşek objeleri kesme (varsayılan olarak keser):

```bash
git gc --no-prune
```

- Tüm çıktıları sessize al:

```bash
git gc --quiet
```

- Tam kullanım için yardım göster:

```bash
git gc --help
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

