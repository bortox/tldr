---
author: ['lincc', 'Tan A']
date: 1643487459
title: "pacman --query, TLDR Pages"
description: "pacman --query, Arch Linux paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/pacman.8>.

- Yüklenmiş paket ve sürümleri sırala:

```bash
pacman --query
```

- Sadece özellikle indirilmiş paket ve sürümleri sırala:

```bash
pacman --query --explicit
```

- Hangi paketin belirtilen dosyaya sahip olduğunu bul:

```bash
pacman --query --owns dosya_ismi
```

- İndirilmiş bir pakete dair bilgiyi görüntüle:

```bash
pacman --query --info paket_ismi
```

- Bir paketin içerdiği dosyaları sırala:

```bash
pacman --query --list paket_ismi
```

- Yetim (başka bir pakete bağlılık olarak indirilmiş ancak herhangi bir paket tarafından gerektirilmeyen) paketleri sırala:

```bash
pacman --query --unrequired --deps --quiet
```

- Mevcut depolarda bulunmayan, indirilmiş paketleri sırala:

```bash
pacman --query --foreign
```

- Miadı dolmuş paketleri sırala:

```bash
pacman --query --upgrades
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

