---
author: ['lincc', 'Tan A']
date: 1643487459
title: "pm, TLDR Pages"
description: "pm, Android cihazındaki uygulamalar ile ilgili bilgi göster."
categories: "android"
---
> Daha fazla bilgi: <https://developer.android.com/studio/command-line/adb#pm>.

- İndirilen tüm uygulamaların sırala:

```bash
pm list packages
```

- İndirilen tüm sistem uygulamalarını sırala:

```bash
pm list packages -s
```

- İndirilen tüm üçüncü el uygulamaları sırala:

```bash
pm list packages -3
```

- Belirtilen anahtar kelimelere uyan uygulamaları sırala:

```bash
pm list packages anahtar_kelimeler
```

- Belirtilen uygulamanın APK'sine giden yolu görüntüle:

```bash
pm path uygulama
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | android/*: add Turkish translation (#7595) | 2022-01-02T21:39:37 | [8a70c9b0d51c](https://github.com/tldr-pages/tldr/commit/8a70c9b0d51c8b192391848645e95d20e88cb4eb)

