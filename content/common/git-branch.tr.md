---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git branch"
description: "git branch, Dallar ile çalışmak için kullanılan ana Git komutu."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-branch>.

- Yerel dalları göster. Mevctu dal `*` ile vurgulanır:

```bash
git branch
```

- Tüm dalları (yerel ve uzak bağlantıda olan) göster:

```bash
git branch -a
```

- Mevcut dalın ismini göster:

```bash
git branch --show-current
```

- Mevcut commit'e dayanarak yeni bir dal oluştur:

```bash
git branch dal_ismi
```

- Belirtilen commit'e dayanarak yeni bir dal oluştur:

```bash
git branch dal_ismi commit_değeri
```

- Bir dalı yeniden adlandır:

```bash
git branch -m eski_dal_ismi yeni_dal_ismi
```

- Yerel bir dalı sil:

```bash
git branch -d dal_ismi
```

- Uzaktaki bir dalı sil:

```bash
git push uzak_bağlantı --delete uzak_dal_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

