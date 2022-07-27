---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git notes, TLDR Pages"
description: "git notes, Nesne notları ekle veya incele."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-notes>.

- Tüm notları ve bağlı oldukları nesneleri sırala:

```bash
git notes list
```

- Belirtilen nesneye bağlanan tüm notları sırala (varsayılan HEAD'dedir):

```bash
git notes list [nesne]
```

- Belirtilen nesneye bağlanan tüm notları göster (varsayılan HEAD'dedir):

```bash
git notes show [nesne]
```

- Belirtilen nesneye bir not ekle (varsayılan metin editörü açılır):

```bash
git notes append nesne
```

- Mesajı belirterek belirtilen nesneye bir not ekle:

```bash
git notes append --message="messaj_yazısı"
```

- Varolan bir notu düzenle (varsayılan HEAD'dedir):

```bash
git notes edit [nesne]
```

- Bir notu bir nesneden öbürüne kopyala:

```bash
git notes copy kaynak_nesne hedef_nesne
```

- Belirtilen nesneye eklenen tüm notları sil:

```bash
git notes remove nesne
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

