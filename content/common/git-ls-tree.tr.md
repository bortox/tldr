---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git ls-tree, TLDR Pages"
description: "git ls-tree, Bir ağaç nesnesinin içeriklerini sırala."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-ls-tree>.

- Bir daldaki ağacın içeriklerini sırala:

```bash
git ls-tree dal_name
```

- Bir commit üstündeki ağacın içeriklerini alt ağaçlara ayırarak sırala.

```bash
git ls-tree -r commit_değeri
```

- Bir commit üstündeki ağacın yalnızca dosya isimlerini göster:

```bash
git ls-tree --name-only commit_değeri
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

