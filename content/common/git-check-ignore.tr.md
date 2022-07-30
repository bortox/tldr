---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git check-ignore"
description: "git check-ignore, Git yoksayma / dışlama ('.gitignore') dosyalarını analiz et."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-check-ignore>.

- Bir dosya veya dizinin yoksayıldığı veya sayılmadığını kontrol et:

```bash
git check-ignore örnek/dosya_veya_dizin
```

- Birden fazla dosya veya dizinin yoksayıldığı veya sayılmadığını kontrol et:

```bash
git check-ignore örnek/dosya örnek/dizin
```

- Her bir satıra tekabül edecek şekilde stdin'den yolisimleri kullan:

```bash
git check-ignore --stdin < örnek/dosya_sırası
```

- İndeksi kontrol etme:

```bash
git check-ignore --no-index örnek/dosya_veya_dizin
```

- Her yol için eşleşen desene dair detayları dahil et:

```bash
git check-ignore --verbose örnek/dosya_veya_dizin
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

