---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git-grep"
description: "git-grep, Belirtilen söz dizisini bir deponun geçmişi dahil tüm dosyalarında ara."
categories: "common"
---
> Sıradan `grep` komutundaki birçok ek bu komut için de aynen geçerlidir.

> Daha fazla bilgi: <https://git-scm.com/docs/git-grep>.

- İzlenen dosyalarda belirtilen söz dizisini ara:

```bash
git grep söz_dizisi
```

- İzlenen dosyalarda belirtilen desene uygun, belirtilen söz dizisini ara:

```bash
git grep söz_dizisi -- file_glob_pattern
```

- Alt modüller de dahil olmak üzere izlenen dosyalarda belirtilen söz dizisini ara:

```bash
git grep --recurse-submodules söz_dizisi
```

- Belirtilen depo geçmişinde belirtilen söz dizisini ara:

```bash
git grep söz_dizisi HEAD~2
```

- Belirtilen söz dizisini tüm dallarda ara:

```bash
git grep söz_dizisi $(git rev-list --all)
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

