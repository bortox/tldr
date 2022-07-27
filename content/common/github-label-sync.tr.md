---
author: ['Axel Navarro', 'lincc', 'Tan A']
date: 1643487459
title: "github-label-sync, TLDR Pages"
description: "github-label-sync, GitHub etiketlerini senkronize etmeye yarayan komut satırı arayüzü."
categories: "common"
---
> Daha fazla bilgi: <https://github.com/Financial-Times/github-label-sync>.

- Yerel bir `labels.json` dosyası kullanarak etiketleri senkronize et:

```bash
github-label-sync --access-token token depo_ismi
```

- Belirli bir etiketlenen JSON dosyası kullanarak etiketleri senkronize et:

```bash
github-label-sync --access-token token --labels url|örnek/json_dosyası depo_ismi
```

- Programı etiketleri gerçekten senkronize etmeden çalıştır:

```bash
github-label-sync --access-token token --dry-run depo_ismi
```

- `labels.json` içinde olmayan etiketleri sakla:

```bash
github-label-sync --access-token token --allow-added-labels depo_ismi
```

- `GITHUB_ACCESS_TOKEN` ortam değişkenini kullanarak senkronize et:

```bash
github-label-sync depo_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | github-label-sync: use repo as more information link (#7591) | 2021-12-31T13:21:30 | [5283cc7c42e6](https://github.com/tldr-pages/tldr/commit/5283cc7c42e69b9d816fb49e9b46c7e1860ba373)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)

