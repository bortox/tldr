---
author: ['marchersimon', 'Tan A']
date: 1659075216
title: "xterm, TLDR Pages"
description: "xterm, X Ekran Sistemi için terminal öykünücüsü."
categories: "linux"
---
> Daha fazla bilgi: <https://manned.org/xterm>.

- `Örnek` başlığına sahip bir terminal aç:

```bash
xterm -T Örnek
```

- Terminali tam ekran modunda aç:

```bash
xterm -fullscreen
```

- Terminali lacivert arkaplan ve sarı ön plan (font rengi) ile aç:

```bash
xterm -bg darkblue -fg yellow
```

- Terminali satır başına 100 karakter ve sütun başına 35 satır sığacak şekilde, x=200px y=20px koordinatlarında aç:

```bash
xterm -geometry 100x35+200+20
```

- Terminali bir Serif fontu ve 20'ye eşit olan bir font büyüklüğü ile aç:

```bash
xterm -fa "Serif" -fs 20
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | xterm: add Turkish translation (#5332) | 2021-03-02T12:09:19 | [05fe483fa7cb](https://github.com/tldr-pages/tldr/commit/05fe483fa7cb0a0e172626e016c3fc33e102e0f4)

