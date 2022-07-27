---
author: ['lincc', 'Tan A']
date: 1643487459
title: "pacman --remove, TLDR Pages"
description: "pacman --remove, Arch Linux paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/pacman.8>.

- Bu alt komut için yardım göster:

```bash
pacman --remove --help
```

- Bir paket ve bağlılıklarını sil:

```bash
sudo pacman --remove --recursive paket_ismi
```

- Bir paketi ve onun hem bağlılıklarını, hem de konfigürasyon dosyalarını sil:

```bash
sudo pacman --remove --recursive --nosave paket_ismi
```

- Bir paketi telkin olmaksızın sil:

```bash
sudo pacman --remove --noconfirm paket_ismi
```

- Yetim (başka bir pakete bağlılık olarak indirilmiş ancak herhangi bir paket tarafından gerektirilmeyen) paketleri sil:

```bash
sudo pacman --remove --recursive --nosave $(pacman --query --unrequired --deps --quiet)
```

- Bir paketi ve ona bağlı olan tüm öbür paketleri sil:

```bash
sudo pacman --remove --cascade paket_ismi
```

- (Bir paketin silinme durumunda) Etkilenecek paketleri (silmeden) listele:

```bash
pacman --remove --print paket_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

