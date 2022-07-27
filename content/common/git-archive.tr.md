---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git archive, TLDR Pages"
description: "git archive, İsimlendirilmiş bir ağaçtan dosyaların arşivini oluştur."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-archive>.

- Mevcut HEAD'deki içerik ile bir tar arşivi oluştur ve içeriği standart çıktı biçiminde göster:

```bash
git archive --verbose HEAD
```

- Mevcut HEAD'deki içerik ile bir zip arşivi oluştur ve içeriği standart çıktı biçiminde göster:

```bash
git archive --verbose --format=zip HEAD
```

- Yukarıda yazan madde ile aynı şeyi yap, ama zip arşivini belirtilen dosya olarak yaz:

```bash
git archive --verbose --output=örnek/arşiv/dosyası.zip HEAD
```

- Belirtilmiş bir daldaki son commitlerin içeriğinden bir tar arşivi oluştur:

```bash
git archive --output=örnek/arşiv/dosyası.tar dal_ismi
```

- Belirtilmiş bir dizindeki içeriklerden tar arşivi oluştur:

```bash
git archive --output=örnek/arşiv/dosyası.tar HEAD:örnek/dizin
```

- Bir takım dosyayı belirtilmiş bir dizinin içinde arşivlemek için başlarına yol ekle:

```bash
git archive --output=örnek/arşiv/dosyası.tar --prefix=başlarına/yol/eklenecek/dosyalar/ HEAD
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

