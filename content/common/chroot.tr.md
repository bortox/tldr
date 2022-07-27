---
author: ['marchersimon', 'Dario Vladović', 'lincc', 'Tan A']
date: 1643487459
title: "chroot, TLDR Pages"
description: "chroot, Komut veya etkileşimli komut satırını özel kök diziniyle çalıştırır."
categories: "common"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/chroot>.

- Komutu yeni kök dizini olarak çalıştır:

```bash
chroot yeni/kok/yolu komut
```

- Kullanılacak kullanıcı ve grubu (ID veya isim) belirle:

```bash
chroot --userspec=kullanici:grup
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chroot: add more information link (#5602) | 2021-03-30T15:50:36 | [b8f38025f36c](https://github.com/tldr-pages/tldr/commit/b8f38025f36c58be3d109949f4badf9e062b43e0)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | chroot, cmake: add Turkish translation (#5173) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-23T21:36:23 | [3a1609b196d6](https://github.com/tldr-pages/tldr/commit/3a1609b196d6a04109750f124e1fa1ff4f0560e1)

