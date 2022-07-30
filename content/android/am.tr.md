---
author: ['Tan A', 'lincc']
date: 1643487459
title: "am"
description: "am, Android aktivite yöneticisi."
categories: "android"
---
> Daha fazla bilgi: <https://developer.android.com/studio/command-line/adb#am>.

- Belirtilmiş bir aktiviteyi başlat:

```bash
am start -n com.android.settings/.Settings
```

- Bir aktivite başlatıp veriyi ona aktar:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Belirtilmiş bir eylem ve kategoriyi karşılayan bir aktivite başlat:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Bir kastı URI'a çevir:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | am: add Turkish translation (#7187) | 2021-11-04T21:10:03 | [664ac4843b6a](https://github.com/tldr-pages/tldr/commit/664ac4843b6a3f9e543fece93a771ddfa6a70525)

