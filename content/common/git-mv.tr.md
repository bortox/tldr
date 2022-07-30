---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git mv"
description: "git mv, Dosyaları taşı veya yeniden adlandır ve Git indeksini güncelle."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-mv>.

- Depo içindeki dosyayı taşı ve bu hareketi sonraki commit'e ekle:

```bash
git mv dosya/konumu yeni/dosya/konumu
```

- Dosyayı yeniden adlandır ve yeniden adlandırma hareketini sonraki commit'e ekle:

```bash
git mv dosya_ismi yeni_dosya_ismi
```

- Eğer varsa belirtilen hedefteki dosyanın üstüne yaz:

```bash
git mv --force dosya hedef
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

