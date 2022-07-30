---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git check-ref-format"
description: "git check-ref-format, Girilen referans isminin kabul edilebilir olup olmadığını kontrol eder, ve eğer kabul edilemezse sıfır olmayan bir çıktı verir."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-check-ref-format>.

- Belirtilen referans ismini biçimini kontrol et:

```bash
git check-ref-format refs/head/referans_ismi
```

- Son kontrol edilen dalın ismini göster:

```bash
git check-ref-format --branch @{-1}
```

- Bir referans ismi dosyasını normalleştir:

```bash
git check-ref-format --normalize refs/head/referans_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

