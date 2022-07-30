---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git describe"
description: "git describe, Bir nesneye varolan referans üzerinden insanlar tarafından okunabilecek biçimde olan bir isim ver:"
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-describe>.

- Mevcut commit için (en son eklenmiş etiket, ilave commit'lerin sayısı ve kısaltılmış commit değerini içeren) özel bir isim oluştur:

```bash
git describe
```

- Kısaltılmış commit değeri için 4 haneli bir isim oluştur:

```bash
git describe --abbrev=4
```

- Etiket referans yolu ile bir isim oluştur:

```bash
git describe --all
```

- Bir Git etiketini açıkla:

```bash
git describe v1.0.0
```

- Belirtilen daldaki son commit için bir isim oluştur:

```bash
git describe dal_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

