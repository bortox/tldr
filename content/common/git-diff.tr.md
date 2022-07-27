---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git diff, TLDR Pages"
description: "git diff, İzlenen dosyalara değişiklikleri göster."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-diff>.

- Sahnelenmemiş, commit'lenmemiş değişiklikleri göster:

```bash
git diff
```

- Sahnelenmiş olanlar da dahil olmak üzere tüm commit'lenmemiş değişiklikleri göster:

```bash
git diff HEAD
```

- Yalnızca sahnelenmiş (eklenmiş ancak commit'lenmemiş) değişiklikleri göster:

```bash
git diff --staged
```

- Belirtilen bir tarihten itibaren yapılmış tüm commit'lerdeki değişiklikleri göster:

```bash
git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}'
```

- Belirtilen bir commit'ten itibaren yalnızca üzerinde değişiklik yapılmış dosyaların ismini göster:

```bash
git diff --name-only commit
```

- Belirtilen bir commit'ten itibaren yapılmış dosya oluşturma, yeniden adlandırma ve mod değişim işlemlerini göster:

```bash
git diff --summary commit
```

- Tek bir dosyayı iki dal veya commit arasında karşılaştır:

```bash
git diff dal_1..dal_2 [--] örnek/dosya
```

- Mevcut daldaki farklı dosyaları başka bir daldakilerle karşılaştır:

```bash
git diff dal:örnek/dosya2 örnek/dosya
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

