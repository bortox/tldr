---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git cherry-pick, TLDR Pages"
description: "git cherry-pick, Varolan commit'ler ile getirilen yenilikleri mevcut dala uygula."
categories: "common"
---
> Değişiklikleri başka bir dala aktarmak için, önce `git checkout` komutu kullanılmalıdır.

> Daha fazla bilgi: <https://git-scm.com/docs/git-cherry-pick>.

- Mevcut dala bir commit uygula:

```bash
git cherry-pick commit_ismi
```

- Mevcut dala belirtilmiş aralıktaki kadar commit uygula (ayrıca `git rebase --onto` komutunun araştırılması önerilir):

```bash
git cherry-pick ilk_commit~..son_commit
```

- Mevcut dala birçok (ardışık olmayan) commit uygula:

```bash
git cherry-pick commit_1 commit_2
```

- Bir commit'in değişikliklerini, herhangi bir yeni commit oluşturmadan çalışan dizine ekle:

```bash
git cherry-pick -n commit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

