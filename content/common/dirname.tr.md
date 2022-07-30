---
author: ['marchersimon', 'Dario Vladović', 'Tan A', 'lincc']
date: 1643487459
title: "dirname"
description: "dirname, Belirtilen dosya veya yolun ana dizinini hesaplar."
categories: "common"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/dirname>.

- Belirtilen yolun ana dizinini hesapla:

```bash
dirname dosya_veya_dizine/giden/yol
```

- Birden çok yolun ana dizinini hesapla:

```bash
dirname dosya_veya_dizine/giden/yol_1 dosya_veya_dizine/giden/yol_2
```

- Komut çıktısını yeni satır yerine NUL karakteri ile sınırlandırma (`xargs` yazılımı ile kullanırken işe yarar):

```bash
dirname --zero dosya_veya_dizine/giden/yol_1 dosya_veya_dizine/giden/yol_2
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirname: add link (#5604) | 2021-03-30T15:55:16 | [016c255e46ff](https://github.com/tldr-pages/tldr/commit/016c255e46ff9a07e2a8bf279a039cb6cfddfdb8)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | dirname, dirs, dirsearch: add Turkish translation (#5320) | 2021-03-07T00:09:27 | [ed353b068bab](https://github.com/tldr-pages/tldr/commit/ed353b068bab960c11a80e84a2becf109c4014d7)

