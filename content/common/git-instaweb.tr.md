---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git instaweb"
description: "git instaweb, gitweb sunucusu başlatmak için yardımcı araç."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-instaweb>.

- Mevcut Git deposu için bir gitweb sunucusu başlat:

```bash
git instaweb --start
```

- Yalnızca yerel ağda başlat:

```bash
git instaweb --start --local
```

- Belirtilmiş bir port'da başlat:

```bash
git instaweb --start --port 1234
```

- Belirtilmiş bir http daemon'u kullan:

```bash
git instaweb --start --httpd lighttpd|apache2|mongoose|plackup|webrick
```

- Ayrıca bir ağ tarayıcısını otomatik olarak başlat:

```bash
git instaweb --start --browser
```

- Çalışan mevcut gitweb sunucusunu durdur:

```bash
git instaweb --stop
```

- Çalışan mevcut gitweb sunucusunu yeniden başlat:

```bash
git instaweb --restart
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

