---
author: ['lincc', 'Tan A']
date: 1643487459
title: "input, TLDR Pages"
description: "input, Olay kodlarını ve dokunmatik ekran mimiklerini bir Android cihazına yolla."
categories: "android"
---
> Bu komut yalnızca `adb shell` ile kullanılabilir.

> Daha fazla bilgi: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Bir Android cihazına tek karakter için etkinlik kodu gönder:

```bash
input keyevent etkinlik_kodu
```

- Bir Android cihazına yazı gönder (`%s` boşlukları temsil eder):

```bash
input text "yazı"
```

- Bir Android cihazına tek dokunuş gönder:

```bash
input tap x_poz y_poz
```

- Bir Android cihazına kaydırma mimiği gönder:

```bash
input swipe x_başlangıç y_başlangıç x_son y_son ms_süre
```

- Bir Android cihazına kaydırma mimiği kullanarak uzun dokunuş gönder:

```bash
input swipe x_poz y_poz x_poz y_poz ms_süre
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | add input.md to tr (#7188) | 2021-10-27T20:34:29 | [70f44e110125](https://github.com/tldr-pages/tldr/commit/70f44e110125e7053a22e12631f2e991b83b85f0)

