---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git shortlog, TLDR Pages"
description: "git shortlog, 'git log' çıktısını özetle."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-shortlog>.

- Yapılan tüm commit'lerin yazar ismiyle alfabetik olarak guruplanmış özetini göster:

```bash
git shortlog
```

- Yapılan tüm commit'lerin en çok commit yapan yazar ismi en üstte olacak şekilde özetini göster:

```bash
git shortlog -n
```

- Yapılan tüm commit'lerin yazar bilgilerini (isim ve e-posta) gösterecek şekilde özetini göster:

```bash
git shortlog -c
```

- En son yapılan 5 commit'in özetini göster (sürüm aralığı belirt):

```bash
git shortlog HEAD~5..HEAD
```

- Mevcut daldaki tüm kullanıcıları, e-postalarını ve yaptıkları commit sayısını göster:

```bash
git shortlog -sne
```

- Tüm dallardaki tüm kullanıcıları, e-postalarını ve yaptıkları commit sayısını göster:

```bash
git shortlog -sne --all
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

