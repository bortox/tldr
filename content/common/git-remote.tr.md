---
author: ['Tan A']
date: 1640780938
title: "git remote"
description: "git remote, İzlenen depolar dizisini (uzak bağlantıları) yönet."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-remote>.

- Varolan uzak bağlantıların isim ve URL'leriyle bir listesini göster:

```bash
git remote -v
```

- Uzak bağlantı ile ilgili bilgi göster:

```bash
git remote show uzak_bağlantı_ismi
```

- Uzak bağlantı ekle:

```bash
git remote add uzak_bağlantı_ismi uzak_bağlantı_url'si
```

- Uzak bağlantının URL'sini değiştir:

```bash
git remote set-url uzak_bağlantı_ismi yeni_url
```

- Uzak bağlantıyı sil:

```bash
git remote remove uzak_bağlantı_ismi
```

- Uzak bağlantıyı yeniden adlandır:

```bash
git remote rename eski_isim yeni_isim
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

