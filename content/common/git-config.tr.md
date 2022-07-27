---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git config, TLDR Pages"
description: "git config, Git depoları için yazılan kişisel konfigürasyon seçeneklerini yönet."
categories: "common"
---
> Bu konfigürasyonlar lokal (mevcut depo için) veya evrensel (mevcut kullanıcı için) olabilir.

> Daha fazla bilgi: <https://git-scm.com/docs/git-config>.

- Yalnızca (mevcut depodaki `.git/config`'de saklanan) yerel konfigürasyon kayıtlarını sırala:

```bash
git config --list --local
```

- Yalnızca (bilgisayardaki `~/.gitconfig`'de saklanan) evrensel konfigürasyon kayıtlarını sırala:

```bash
git config --list --global
```

- Yerel veya evrensel olarak tanımlanan tüm konfigürasyon kayıtlarını sırala:

```bash
git config --list
```

- Belirtilen bir konfigürasyon kaydının değerini öğren:

```bash
git config alias.unstage
```

- Belirtilen bir konfigürasyon kaydının evrensel değerini belirle:

```bash
git config --global alias.unstage "reset HEAD --"
```

- Evrensel bir konfigürasyon kaydını varsayılan değerine geri al:

```bash
git config --global --unset alias.unstage
```

- Mevcut depodaki Git konfigürasyonunu varsayılan metin düzenleyici ile düzenle:

```bash
git config --edit
```

- Evrensel Git konfigürasyonunu varsayılan metin düzenleyici ile düzenle:

```bash
git config --global --edit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

