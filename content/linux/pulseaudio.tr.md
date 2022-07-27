---
author: ['marchersimon', 'lincc', 'Tan A']
date: 1643487459
title: "pulseaudio, TLDR Pages"
description: "pulseaudio, Ses sistem arkaplan uygulaması ve yöneticisi."
categories: "linux"
---
> Daha fazla bilgi: <https://www.freedesktop.org/wiki/Software/PulseAudio/>.

- Pulseaudio'nun çalışıp çalışmadığını kontrol et (sıfır olmayan çıktı, çalışmadığı anlamına gelir):

```bash
pulseaudio --check
```

- Pulseaudio'yu arkaplanda çalıştır:

```bash
pulseaudio --start
```

- Arkaplanda çalışan tüm pulseaudio uygulamalarını öldür:

```bash
pulseaudio --kill
```

- Müsait modülleri sırala:

```bash
pulseaudio --dump-modules
```

- Belirtilen argümanlarla bir modülü mevcut çalışan arkaplan uygulamasına yükle:

```bash
pulseaudio --load="modül_ismi argümanlar"
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pulseaudio: add link (#6072) | 2021-05-31T14:05:19 | [89013d28a523](https://github.com/tldr-pages/tldr/commit/89013d28a5233cd765de215ea65b8a1bfd34ae29)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | pulseaudio: add Turkish translation (#5330) | 2021-03-02T12:28:55 | [623b6e53ec61](https://github.com/tldr-pages/tldr/commit/623b6e53ec61027ac289f169e8bd19d8ce583593)

