---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git svn, TLDR Pages"
description: "git svn, Bir alt sürüm deposu ve Git arasında çift yönlü operasyon."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-svn>.

- Bit SVN deposunu klonla:

```bash
git svn clone https://ornek.com/altsürüm_deposu yerel_dizin
```

- Bir SVN deposunu belirtilen düzenleme numarasından başlayarak klonla:

```bash
git svn clone -r1234:HEAD https://svn.ornek.net/altsürüm/depo yerel_dizin
```

- Uzak SVN deposundan yerel klonu güncelle:

```bash
git svn rebase
```

- Git HEAD'i değiştirmeden uzak SVN deposundan güncellemeleri çek:

```bash
git svn fetch
```

- SVN deposuna geri commit'le:

```bash
git svn dcommit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

