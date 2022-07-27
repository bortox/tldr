---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git difftool, TLDR Pages"
description: "git difftool, Harici diff araçları kullanarak dosya değişimlerini göster. `git diff` ile aynı ayar ve argümanları destekler."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-difftool>.

- Müsait diff araçlarını göster:

```bash
git difftool --tool-help
```

- Varsayılan diff aracını birleştirmeye ayarla:

```bash
git config --global diff.tool "meld"
```

- Varsayılan diff aracını sahnelenmiş değişiklikleri göstermek için kullan:

```bash
git difftool --staged
```

- Verilen commit'den itibaren yapılmış değişiklikleri göstermek için (opendiff) kullan:

```bash
git difftool --tool=opendiff commit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

