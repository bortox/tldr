---
author: ['lincc', 'Tan A']
date: 1643487459
title: "cp, TLDR Pages"
description: "cp, Dosya ve dizinleri kopyala."
categories: "linux"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/cp>.

- Bir dosyayı başka bir konuma kopyala:

```bash
cp örnek/yol/kaynak_dosya.ext örnek/yol/hedef_dosya.ext
```

- Bir dosyayı ismini değiştirmeden başka bir dizine kopyala:

```bash
cp örnek/yol/kaynak_dosya.ext örnek/yol/hedef_ana_dizin
```

- Bir dizinin içeriğini başka bir konuma tekrarlı şekilde kopyala (eğer belirtilen konum varsa dizin onun içine kopyalanır):

```bash
cp -r örnek/yol/kaynak_dizin örnek/yol/hedef_dizin
```

- Bir dizini tekrarlı şekilde ayrıntılı modda kopyala (dosyaları kopyalandıkları gibi gösterir):

```bash
cp -vr örnek/yol/kaynak_dizin örnek/yol/hedef_dizin
```

- Metin dosyalarını interaktif modda başka bir konuma kopyala (üstüne yazmadan önce kullanıcıyı bilgilendirir):

```bash
cp -i *.txt örnek/yol/hedef_dizin
```

- Kopyalamadan önce sembolik linkleri izle:

```bash
cp -L link örnek/yol/hedef_dizin
```

- Kopyalarken kaynak dosyalarının tam konumunu belirt:

```bash
cp --parents kaynak/örnek/yol/dosya örnek/yol/hedef_dosya
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | cp: add Turkish translation (#7362) | 2021-11-03T17:13:34 | [4f3bc34a948c](https://github.com/tldr-pages/tldr/commit/4f3bc34a948cbc4e605fe9b4536323a4ebf17698)

