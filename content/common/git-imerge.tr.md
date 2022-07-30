---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git-imerge"
description: "git-imerge, İki git dalı arasında aşamalı olarak birleştirme veya taban değiştirme işlemlerini uygula."
categories: "common"
---
> Dallar arasındaki uyuşmazlıklar özel commitler ile bölüşülerek uyuşmazlıkları çözmek kolaylaştırılır.

> Daha fazla bilgi: <https://github.com/mhagger/git-imerge>.

- imerge bazlı taban değiştirme işlemini başlat (işlemden önce tabanı değiştirilmek istenen dalı kontrol et):

```bash
git imerge rebase yerine_geçilecek_dal
```

- imerge bazlı birleştirme işlemini başlat (işlemden önce birleştirilmek istenen dalı kontrol et):

```bash
git imerge merge birleştirilecek_dal
```

- Devam eden birleştirme ve taban değiştirme işlemlerinin ASCII diagramını göster:

```bash
git imerge diagram
```

- Uyuşmazlıkları çözdükten sonra imerge işlemine devam et (önce `git add` komutu ile uyuşmayan dosyaları ekle):

```bash
git imerge continue --no-edit
```

- Tüm uyuşmazlıklar çözüldükten sonra imerge işlemini sonlandır:

```bash
git imerge finish
```

- imerge işlemini sonlandır ve belirtilen eski bir dala geri dön:

```bash
git-imerge remove && git checkout eski_dal
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

