---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git show-branch"
description: "git show-branch, Dalları ve içerdikleri commit'leri göster:"
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-show-branch>.

- Bir daldaki son commit'lerin bir özetini göster:

```bash
git show-branch dal_ismi|referans|commit
```

- Çeşitli commit veya daldaki commit'lerin geçmişini karşılaştır:

```bash
git show-branch dal_ismi|referans|commit
```

- Tüm uzak takip dallarını karşılaştır:

```bash
git show-branch --remotes
```

- Hem yerel, hem de uzak takip dallarını karşılaştır:

```bash
git show-branch --all
```

- Tüm dallardaki son commit'leri sırala:

```bash
git show-branch --all --list
```

- Belirtilen dalı mevcut dal ile karşılaştır:

```bash
git show-branch --current commit|dal_ismi|referans
```

- Bağlı isim yerine commit ismini görüntüle:

```bash
git show-branch --sha1-name --current current|dal_ismi|referans
```

- Commit'lerin ortak atasından sonraki commit'leri belirtilen sayı kadar görüntüle:

```bash
git show-branch --more 5 commit|dal_ismi|referans commit|dal_ismi|referans ...
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

