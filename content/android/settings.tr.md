---
author: ['lincc', 'Tan A']
date: 1643487459
title: "settings, TLDR Pages"
description: "settings, Android işletim sistemi ile ilgili bilgi al."
categories: "android"
---
> Daha fazla bilgi: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- `global` isim alanındaki ayarların sırasını görüntüle:

```bash
settings list global
```

- Belirtilen ayarın değerini al:

```bash
settings get global airplane_mode_on
```

- Bir ayarın değerini belirle:

```bash
settings put system screen_brightness 42
```

- Belirtilen ayarı sil:

```bash
settings delete secure screensaver_enabled
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | android/*: add Turkish translation (#7595) | 2022-01-02T21:39:37 | [8a70c9b0d51c](https://github.com/tldr-pages/tldr/commit/8a70c9b0d51c8b192391848645e95d20e88cb4eb)

