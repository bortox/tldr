---
author: ['Mehmet Mallı', 'lincc']
date: 1643487459
title: "nginx"
description: "nginx, Nginx web sunucusu."
categories: "common"
---
> Daha fazla bilgi: <https://nginx.org/en/>.

- Varsayılan konfigürasyon dosyasıyla sunucuyu başlat:

```bash
nginx
```

- Özel bir konfigürasyon dosyasıyla sunucuyu başlat:

```bash
nginx -c konfigürasyon_dosyası
```

- Konfigürasyon dosyasındaki her göreceli dosya yolu için bir ön ek ile sunucuyu başlat:

```bash
nginx -c konfigürasyon_dosyası -p göreceli/dosya/yolu/ön/eki
```

- Çalışan sunucuyu etkilemeden konfigürasyon dosyasını test et:

```bash
nginx -t
```

- Aksamasız bir sinyal göndererek konfigürasyonu tekrar yükle:

```bash
nginx -s reload
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Mehmet Mallı](mailto:mallimehmet@gmail.com) | nginx: add Turkish translation (#6772) | 2021-10-04T18:03:12 | [341e1875c50d](https://github.com/tldr-pages/tldr/commit/341e1875c50dec01541e76689128a271118d2a53)

