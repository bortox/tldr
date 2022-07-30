---
author: ['Tan A', 'lincc']
date: 1643487459
title: "pacman --sync"
description: "pacman --sync, Arch Linux paket yönetim aracı."
categories: "linux"
---
> Daha fazla bilgi: <https://man.archlinux.org/man/pacman.8>.

- Yeni bir paket indir::

```bash
sudo pacman --sync paket_ismi
```

- Tüm paketleri senkronize et ve güncelle (bahsi geçen paketleri güncellemeden indirmek için `--downloadonly` eki gereklidir)

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Tüm paketleri güncelle ve telkin olmaksızın yeni bir tane indir:

```bash
sudo pacman --sync --refresh --sysupgrade --noconfirm paket_ismi
```

- Paket veritabanını girilen ifade ile arat:

```bash
pacman --sync --search "arama_şablonu"
```

- Bir paket hakkında bilgi görüntüle:

```bash
pacman --sync --info paket_ismi
```

- Bir paket güncellemesi sırasında çakışan dosyaların üstüne yaz:

```bash
sudo pacman --sync --refresh --sysupgrade --overwrite örnek_dosya
```

- Tüm paketleri senkronize et ve güncelle, ancak belli bir paketi yoksay:

```bash
sudo pacman --sync --refresh --sysupgrade --ignore paket_ismi
```

- Kullanılmayan paket ve kullanılmamış depoları çerezlerden sil (tüm paketlerin çerezlerini temizlemek için `--clean` eki iki kez kullanılmalıdır):

```bash
sudo pacman --sync --clean
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pacman*: add Turkish translations (#5326) | 2021-03-01T14:57:17 | [e6bc322a970a](https://github.com/tldr-pages/tldr/commit/e6bc322a970aca9d969c454877fc7f06e400ef87)

