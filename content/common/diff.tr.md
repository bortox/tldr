---
author: ['Desc4rtes']
date: 1635765393
title: "diff, TLDR Pages"
description: "diff, Dosyaları ve dizinleri karşılaştırın."
categories: "common"
---
> Daha fazla bilgi: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Dosyaları karşılaştır (`eski_dosya`'yı `yeni_dosya`'ya dönüştürmek için yapılan değişiklikleri listeler):

```bash
diff eski_dosya yeni_dosya
```

- Boşlukları yok sayarak dosyaları karşılaştırın:

```bash
diff --ignore-all-space eski_dosya yeni_dosya
```

- Farkları yan yana göstererek dosyaları karşılaştırın:

```bash
diff --side-by-side eski_dosya yeni_dosya
```

- Farkları birleştirilmiş biçimde (`git diff` tarafından kullanıldığı gibi) göstererek dosyaları karşılaştırın:

```bash
diff --unified eski_dosya yeni_dosya
```

- Dizinleri yinelemeli olarak karşılaştırın (farklı dosya/dizin adlarını ve dosyalarda yapılan değişiklikleri gösterir):

```bash
diff --recursive eski_dizin yeni_dizin
```

- Dizinleri karşılaştırın, yalnızca farklı olan dosyaların adlarını gösterin:

```bash
diff --recursive --brief eski_dizin yeni_dizin
```

- Git için iki metin dosyasının farklarından, var olmayan dosyaları ise boş olarak değerlendirerek bir yama dosyası oluşturun:

```bash
diff --text --unified --new-file eski_dosya yeni_dosya > fark.patch
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Desc4rtes](mailto:cheryyblossom.ai@gmail.com) | diff: add Turkish translation (#7271) * date: add Turkish translation * Delete su.md * su: add Turkish translation * diff: add Turkish [...] | 2021-11-01T12:16:33 | [afb155771217](https://github.com/tldr-pages/tldr/commit/afb1557712174f5e6d370fbd6eee03b51c798ae2)

