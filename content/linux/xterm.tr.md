---
author: ['Tan A']
date: 1614683359
title: "xterm, TLDR Pages"
description: "xterm, X Ekran Sistemi için terminal öykünücüsü."
categories: "linux"
---
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
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | xterm: add Turkish translation (#5332) | 2021-03-02T12:09:19 | [05fe483fa7cb](https://github.com/tldr-pages/tldr/commit/05fe483fa7cb0a0e172626e016c3fc33e102e0f4)

