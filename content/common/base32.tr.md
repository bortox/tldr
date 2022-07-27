---
author: ['marchersimon', 'Dario Vladović', 'lincc', 'Tan A']
date: 1643487459
title: "base32, TLDR Pages"
description: "base32, Bir dosya veya standart veriyi Base32 formatında şifrele veya yalın veri çıktısı olarak deşifre et."
categories: "common"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/base32>.

- Bir dosyayı şifrele:

```bash
base32 dosyaismi
```

- Bir dosyayı deşifre et:

```bash
base32 --decode dosyaismi
```

- stdin'den şifrele:

```bash
herhangibirkomut | base32
```

- stdin'den deşifre et:

```bash
herhangibirkomut | base32 --decode
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base32: add link (#5571) | 2021-03-30T09:11:31 | [30331c3d152d](https://github.com/tldr-pages/tldr/commit/30331c3d152d78ba495f78b7759f04b7bcd46f9f)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | base32: add Turkish translation (#5317) | 2021-03-10T20:49:35 | [9db804476a0d](https://github.com/tldr-pages/tldr/commit/9db804476a0d6cf1483159a6b0f677c1d8f7c690)

