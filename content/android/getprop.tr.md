---
author: ['lincc', 'Tan A']
date: 1643487459
title: "getprop, TLDR Pages"
description: "getprop, Android sistem özellikleri ile ilgili bilgi görüntüle."
categories: "android"
---
> Daha fazla bilgi: <https://manned.org/getprop>.

- Android sistem özellikleri ile ilgili bilgi görüntüle:

```bash
getprop
```

- Belirtilen özellik ile ilgili bilgi görüntüle:

```bash
getprop prop
```

- SDK API seviyesini görüntüle:

```bash
getprop ro.build.version.sdk
```

- Android sürümünü görüntüle:

```bash
getprop ro.build.version.release
```

- Android cihaz modelini görüntüle:

```bash
getprop ro.vendor.product.model
```

- OEM kilit durumunu görüntüle:

```bash
getprop ro.oem_unlock_supported
```

- Android'in Wi-Fi kartının MAC adreslerini görüntüle:

```bash
getprop ro.boot.wifimacaddr
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | android/*: add Turkish translation (#7595) | 2022-01-02T21:39:37 | [8a70c9b0d51c](https://github.com/tldr-pages/tldr/commit/8a70c9b0d51c8b192391848645e95d20e88cb4eb)

