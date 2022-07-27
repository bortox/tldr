---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git stash, TLDR Pages"
description: "git stash, Yerel Git düzenlemelerini geçici bir alanda sakla."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-stash>.

- Yeni (izlenmeyen) dosyalar hariç mevcut değişiklikleri sakla:

```bash
git stash [push -m keyfi_saklama_mesajı]
```

- Yeni (izlenmeyen) dosyalar dahil mevcut değişiklikleri sakla:

```bash
git stash -u
```

- Değiştirilen dosyaların parçalarını etkileşimli şekilde seçip sakla:

```bash
git stash -p
```

- Tüm saklananları göster (saklanan ismi, bağlı olduğu dal ve mesaj gösterilir):

```bash
git stash list
```

- Bir saklananı uygula (varsayılan son saklanandır ve stash@{0} olarak belirtilir):

```bash
git stash apply keyfi_saklanan_veya_commit_ismi
```

- Bir saklananı uygula (varsayılan stash@{0}), ve eğer uygulanması sıkıntı çıkarmıyorsa onu saklanan listesinden kaldır:

```bash
git stash pop keyfi_saklanan_ismi
```

- Bir saklananı bırak (varsayılan stash@{0}):

```bash
git stash drop keyfi_saklanan_ismi
```

- Tüm saklananları bırak:

```bash
git stash clear
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

