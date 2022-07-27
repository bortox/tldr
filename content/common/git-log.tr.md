---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git log, TLDR Pages"
description: "git log, Commit geçmişini göster."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-log>.

- Mevcut olandan başlayarak mevcut çalışma ortamındaki git deposunun commit silsilesini ters kronolojik düzende göster:

```bash
git log
```

- Belirtilen dosya veya dizinin tarihini farklılıklarla beraber göster:

```bash
git log -p dosya/veya/dizin/konumu
```

- Her bir commit'de hangi dosya(lar)ın değiştiğinin önizlemesini göster:

```bash
git log --stat
```

- Mevcut daldaki commit'lerin mesajlarının ilk satırını içeren bir çizelge göster:

```bash
git log --oneline --graph
```

- Bir depodaki commit, etiket ve dalların tamamını içeren bir çizelge göster:

```bash
git log --oneline --decorate --all --graph
```

- Mesajları yalnızca belirtilen ifadeleri içeren commit'leri göster (büyük-küçük harfe duyarsız):

```bash
git log -i --grep aranan_ifade
```

- Belirtilmiş yazardan gelen, belirtilen sayıda commit göster:

```bash
git log -n sayı --author=yazar
```

- İki tarih arasında yapılmış commit'leri göster:

```bash
git log --before=tarih --after=tarih
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

