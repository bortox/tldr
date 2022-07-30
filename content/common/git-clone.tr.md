---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git clone"
description: "git clone, Varolan bir dizini klonla."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-clone>.

- Varolan bir depoyu klonla:

```bash
git clone uzak_bağlantıdaki_depo
```

- Varolan bir depoyu velirtilen dizine klonla:

```bash
git clone uzak_bağlantıdaki_depo örnek/dizin
```

- Varolan bir depo ve onun alt modüllerini klonla:

```bash
git clone --recursive uzak_bağlantıdaki_depo
```

- Yerel bir depoyu klonla:

```bash
git clone -l örnek/yerel/depo
```

- Sessizce klonla:

```bash
git clone -q uzak_bağlantıdaki_depo
```

- Yalnızca en yeni 10 commit'i çekerek varolan bir depoyu klonla (zaman tasarrufu açısından yararlıdır):

```bash
git clone --depth 10 uzak_bağlantıdaki_depo
```

- Yalnızca belirtilen bir dalı çekerek varolan bir depoyu klonla:

```bash
git clone --branch isim --single-branch uzak_bağlantıdaki_depo
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

