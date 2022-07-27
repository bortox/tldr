---
author: ['Oğuz Ersen']
date: 1647493732
title: "atool, TLDR Pages"
description: "atool, Çeşitli biçimlerdeki arşivleri yönetin."
categories: "linux"
---
> Daha fazla bilgi: <https://www.nongnu.org/atool/>.

- Bir zip arşivindeki dosyaları listele:

```bash
atool --list arşiv.zip/dosyasının/yolu
```

- Bir tar.gz arşivini yeni bir alt dizine (veya yalnızca bir dosya içeriyorsa geçerli dizine) çıkart:

```bash
atool --extract arşiv.tar.gz/dosyasının/yolu
```

- İki dosyaya sahip yeni bir 7zip arşivi oluştur:

```bash
atool --add arşiv.7z/dosyasının/yolu dosya1/yolu dosya2/yolu
```

- Geçerli dizindeki tüm zip ve rar arşivlerini çıkart:

```bash
atool --each --extract *.zip *.rar
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | atool, dnf, wl-copy, wl-paste: add Turkish translation (#7837) * wl-copy, wl-paste: fix invalid command options --paste-once is valid [...] | 2022-03-17T06:08:52 | [e7a06bac2805](https://github.com/tldr-pages/tldr/commit/e7a06bac28057862cb80128905031eab5173ff0b)

