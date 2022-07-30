---
author: ['marchersimon', 'Tan A', 'lincc']
date: 1643487459
title: "pacman"
description: "pacman, Arch Linux paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/pacman.8>.

- Tüm paketleri senkronize et ve güncelle:

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Yeni bir paket indir:

```bash
sudo pacman --sync paket_ismi
```

- Bir paket ve bağlılıklarını sil:

```bash
sudo pacman --remove --recursive paket_ismi
```

- Paket veritabanını girilen ifade ile arat:

```bash
pacman --sync --search "arama_şablonu"
```

- İndirilmiş paket ve sürümleri sırala:

```bash
pacman --query
```

- Sadece özellikle belirtilen paket ve sürümleri sırala:

```bash
pacman --query --explicit
```

- Hangi paketin belirtilen dosyaya sahip olduğunu bul:

```bash
pacman --query --owns dosya_ismi
```

- Paket çerezlerini boş alan açmak için temizle:

```bash
sudo pacman --sync --clean --clean
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

