---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git rebase"
description: "git rebase, Bir daldan başka bir dalın üstüne commit'leri tekrar temeller."
categories: "common"
---
> Sıklıkla bir dalı commit'leriyle beraber başka bir tabana "taşımak" için kullanılır.

> Daha fazla bilgi: <https://git-scm.com/docs/git-rebase>.

- Mevcut dalı belirtilen öbür dal üzerine temelle:

```bash
git rebase yeni_taban_dal
```

- Commit'lerin sıralanması, çıkartılması, birleştirilmesi veya modifiye edilmesine izin vermek için tekrar temellemeyi etkileşimli olacak şekilde başlat:

```bash
git rebase -i hedef_taban_dalı_veya_commit_değeri
```

- Bir birleştirme hatası tarafından durdurulan tekrar temelleme işlemini çekişen dosyaları düzenledikten sonra devam ettir:

```bash
git rebase --continue
```

- Birleştirme çatışmasından ötürü durdurulan tekrar temelleme işlemini çekişen commit'leri atlayarak devam ettir:

```bash
git rebase --skip
```

- Devam eden tekrar temelleme işlemini iptal et (örneğin birleştirmede çatışma yaşandığında):

```bash
git rebase --abort
```

- Mevcut dalın bir parçasını belirtilen eski tabandan yeni tabana taşı:

```bash
git rebase --onto yeni_taban eski_taban
```

- Son 3 commit'i etkileşimli olmayacak şekilde yeniden uygula:

```bash
git rebase -i HEAD~5
```

- Herhangi bir çatışmayı çalışan dal sürümünü kurtarmak üzere otomatik olarak çöz (`theirs` argümanı burada ters anlama sahip):

```bash
git rebase -X theirs dal_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

