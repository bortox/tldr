---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git apply"
description: "git apply, İndeks veya dosyalara yama uygula."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-apply>.

- Yamalanan dosyalarla ilgili mesajları yazdır:

```bash
git apply --verbose örnek/dosya
```

- Yamalanan dosyaları indekse uygula ve ekle:

```bash
git apply --index örnek/dosya
```

- Uzak yama dosyası uygula:

```bash
curl https://ornek.com/dosya.patch | git apply
```

- Çıktı için fark statistiği çıkar ve yamayı uygula:

```bash
git apply --stat --apply örnek/dosya
```

- Yamayı tersten uygula:

```bash
git apply --reverse örnek/dosya
```

- Yama sonucunu çalışan ağacı değiştirmeden indekste sakla:

```bash
git apply --cache örnek/dosya
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

