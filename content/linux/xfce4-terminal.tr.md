---
author: ['marchersimon', 'Tan A', 'lincc']
date: 1643487459
title: "xfce4-terminal"
description: "xfce4-terminal, XFCE4 terminal öykünücüsü."
categories: "linux"
---
> Daha fazla bilgi: <https://docs.xfce.org/apps/xfce4-terminal/start>.

- Yeni bir terminal penceresi aç:

```bash
xfce4-terminal
```

- Başlangıç başlığı belirle:

```bash
xfce4-terminal --initial-title "başlangıç_başlığı"
```

- Mevcut terminal penceresinde yeni bir sekme aç:

```bash
xfce4-terminal --tab
```

- Yeni bir terminal penceresini belirlenen bir komutu çalıştırarak aç:

```bash
xfce4-terminal --command "argümanlı_komut"
```

- Çalıştırılan komutun çalışmayı kesme durumunda dahi terminali kapama:

```bash
xfce4-terminal --command "argümanlı_komut" --hold
```

- Her birinde farklı komut çalışacak birçok yeni sekme aç:

```bash
xfce4-terminal --tab --command "komut_a" --tab --command "komut_b"
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xfce4-screenshooter, xfce4-terminal: add link (#6075) | 2021-05-31T19:06:30 | [cfd0b5bd34da](https://github.com/tldr-pages/tldr/commit/cfd0b5bd34da972d7780b0b8580b3fb2af145607)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | xfce-*: add Turkish translation (#5333) | 2021-03-02T12:15:22 | [80f0fbb2ba01](https://github.com/tldr-pages/tldr/commit/80f0fbb2ba01e63ad3ea3a07bdaa45647f12f53d)

