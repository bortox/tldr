---
author: ['marchersimon', 'Tan A', 'lincc']
date: 1660133637
title: "pacman"
description: "pacman, Arch Linux paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/pacman.8>.

- Tüm paketleri senkronize et ve güncelle:

```bash
sudo pacman -Syu
```

- Yeni bir paket indir:

```bash
sudo pacman -S paket_ismi
```

- Bir paket ve bağlılıklarını sil:

```bash
sudo pacman -Rs paket_ismi
```

- Paket veritabanını girilen ifade ile arat:

```bash
pacman -Ss "arama_şablonu"
```

- İndirilmiş paket ve sürümleri sırala:

```bash
pacman -Q
```

- Sadece özellikle belirtilen paket ve sürümleri sırala:

```bash
pacman -Qe
```

- Hangi paketin belirtilen dosyaya sahip olduğunu bul:

```bash
pacman -Qo dosya_ismi
```

- Paket çerezlerini boş alan açmak için temizle:

```bash
sudo pacman -Scc
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: use short options only (#8286) | 2022-08-10T14:13:57 | [1f147d6b91a6](https://github.com/tldr-pages/tldr/commit/1f147d6b91a67044e5f60817a0355d2acd40bb88)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

