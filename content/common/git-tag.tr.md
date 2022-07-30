---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git tag"
description: "git tag, Etiketleri oluştur, sırala, sil veya doğrula."
categories: "common"
---
> Bir etiket, belirtilmiş bir commit'e bağlı statik bir referanstır.

> Daha fazla bilgi: <https://git-scm.com/docs/git-tag>.

- Tüm etiketleri sırala:

```bash
git tag
```

- Belirtilen isim ile mevcut commit'e bağlı bir etiket yarat:

```bash
git tag etiket_ismi
```

- Belirtilen isim ile belirtilen commit'e bağlı bir etiket yarat:

```bash
git tag etiket_ismi commit
```

- Belirtilen mesaja sahip açıklamalı bir etiket yarat:

```bash
git tag etiket_ismi -m etiket_mesajı
```

- Belirtilen isimdeki etiketi sil:

```bash
git tag -d etiket_ismi
```

- Ana projeden güncellenmiş etiketleri al:

```bash
git fetch --tags
```

- Belirtilen commit'i içeren/içermiş tüm etiketleri sırala:

```bash
git tag --contains commit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

