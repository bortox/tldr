---
author: ['marchersimon', 'Dario Vladović', 'lincc', 'Tan A']
date: 1643487459
title: "base64, TLDR Pages"
description: "base64, Bir dosya veya standart veriyi Base64 formatında şifrele veya yalın veri çıktısı olarak deşifre et."
categories: "common"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/base64>.

- Bir dosyayı şifrele:

```bash
base64 dosyaismi
```

- Bir dosyayı deşifre et:

```bash
base64 --decode dosyaismi
```

- stdin'den şifrele:

```bash
herhangibirkomut | base64
```

- stdin'den deşifre et:

```bash
herhangibirkomut | base64 --decode
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base64: add link (#5572) | 2021-03-30T09:06:32 | [59583f4c3ef2](https://github.com/tldr-pages/tldr/commit/59583f4c3ef21258f554c49dc14001e27e3bd4e1)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | base64: add Turkish translation (#5318) | 2021-03-08T21:16:55 | [69bd42d179e2](https://github.com/tldr-pages/tldr/commit/69bd42d179e249b0c267c5939f23e85c7e9c4009)

