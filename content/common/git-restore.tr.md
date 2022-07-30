---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git restore"
description: "git restore, Çalışan ağaç dosyalarını onar. Git sürümü 2.23+ olmalıdır."
categories: "common"
---
> `git checkout` ve `git reset` komutlarına da ayrıca bakılması tavsiye edilir.

> Daha fazla bilgi: <https://git-scm.com/docs/git-restore>.

- Sahnelenmemiş bir dosyayı mevcut commit'in sürümüne kavuştur:

```bash
git restore dosya/konumu
```

- Sahnelenmemiş bir dosyayı belirtilen commit'in sürümüne kavuştur:

```bash
git restore --source commit dosya/konumu
```

- İzlenen dosyalardaki sahnelenmemiş tüm değişiklikleri iptal et:

```bash
git restore :/
```

- Bir dosyayı sahnelenmemiş hale getir:

```bash
git restore --staged dosya/konumu
```

- Tüm dosyaları sahnelenmemiş hale getir:

```bash
git restore --staged :/
```

- Dosyalara yapılan sahnelenmiş veya sahnelenmemiş tüm değişiklikleri iptal et:

```bash
git restore --worktree --staged :/
```

- Onarılacak dosya parçalarını etkileşimli olarak seç:

```bash
git restore --patch
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

