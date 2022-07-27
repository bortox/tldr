---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git subtree, TLDR Pages"
description: "git subtree, Proje bağımlılıklarını alt proje olarak yönetmeye yarayan bir araç."
categories: "common"
---
> Daha fazla bilgi: <https://manpages.debian.org/testing/git-man/git-subtree.1.en.html>.

- Bir Git deposunu alt ağaç olarak ekle:

```bash
git subtree add --prefix=dizin/konumu --squash depo_url'si dal_ismi
```

- Alt ağaç deposunu son commit'ine güncelle:

```bash
git subtree pull --prefix=dizin/konumu depo_url'si dal_ismi
```

- Son alt ağaca kadar olan değişiklikleri alt ağaca commit'le:

```bash
git subtree merge --prefix=dizin/konumu} --squash depo_url'si dal_ismi
```

- Commit'leri bir alt ağaç deposuna yolla:

```bash
git subtree push --prefix=dizin/konumu} depo_url'si dal_ismi
```

- Bir alt ağacın geçmişinden yeni bir proje geçmişi dışa aktar:

```bash
git subtree split --prefix=dizin/konumu} depo_url'si -b dal_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

