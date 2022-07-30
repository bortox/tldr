---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git column"
description: "git column, Kolonlarda veri görüntüle."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-column>.

- Standart çıktıyı çoklu kolonlar olarak biçimlendir:

```bash
ls | git column --mode=column
```

- Standart çıktıyı maksimum `100` birim sütun genişliğinde biçimlendir:

```bash
ls | git column --mode=column --width=100
```

- Standart çıktıyı maksimum `30` birimlik boşluğa sahip situnlar olacak şekilde biçimlendir:

```bash
ls | git column --mode=column --padding=30
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

