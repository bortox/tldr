---
author: ['lincc', 'Tan A']
date: 1643487459
title: "minetestserver, TLDR Pages"
description: "minetestserver, Çok oyunculu sınırsız dünyalı bloklu sanbox sunucusu."
categories: "common"
---
> Ayrıca `minetest` sayfasına bakılması önerilir.

> Daha fazla bilgi: <https://wiki.minetest.net/Setting_up_a_server>.

- Sunucuyu başlar:

```bash
minetestserver
```

- Müsait dünyaları sırala:

```bash
minetestserver --world list
```

- Yüklenecek dünya ismini belirt:

```bash
minetestserver --world dunya_ismi
```

- Müsait oyun ID'lerini sırala:

```bash
minetestserver --gameid list
```

- Kullanılacak oyunu belirt:

```bash
minetestserver --gameid oyun_id'si
```

- Belirtilmiş bir port'u dinle:

```bash
minetestserver --port 34567
```

- Başka bir veritabanı yazılımına göç et:

```bash
minetestserver --migrate sqlite3|leveldb|redis
```

- Sunucuyu başlattıktan sonra interaktif bir terminal aç:

```bash
minetestserver --terminal
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | minetest*: add Turkish translation (#5336) | 2021-03-02T12:42:12 | [f4fc3f06dab7](https://github.com/tldr-pages/tldr/commit/f4fc3f06dab7188322996d5887c99c30a171472b)

