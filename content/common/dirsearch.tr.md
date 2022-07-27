---
author: ['lincc', 'Tan A']
date: 1643487459
title: "dirsearch, TLDR Pages"
description: "dirsearch, Ağ yolu tarayıcı."
categories: "common"
---
> Daha fazla bilgi: <https://github.com/maurosoria/dirsearch>.

- Bir ağ sunucusunu yaygın eklentiler içeren yaygın yollar için tarayın:

```bash
dirsearch --url url --extensions-list
```

- Ağ sunucularını içeren bir listeyi `.php` eklentili yaygın yollar için tarayın:

```bash
dirsearch --url-list örnek/url-listesi.txt --extensions php
```

- Bir ağ sunucusunu yaygın eklentiler içeren belirtilen yollar için tarayın:

```bash
dirsearch --url url --extensions-list --wordlist path/to/url-yol-listesi.txt
```

- Bir ağ sunucusunu çerez kullanarak tarayın:

```bash
dirsearch --url url --extensions php --cookie cookie
```

- Bir ağ sunucusunu `HEAD` HTTP metodunu kullanarak tarayın:

```bash
dirsearch --url url --extensions php --http-method HEAD
```

- Bir ağ sunucusunu tarayın ve sonuçları bir `.json` dosyasına kaydedin:

```bash
dirsearch --url url --extensions php --json-report örnek/rapor_dosyası.json
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | dirname, dirs, dirsearch: add Turkish translation (#5320) | 2021-03-07T00:09:27 | [ed353b068bab](https://github.com/tldr-pages/tldr/commit/ed353b068bab960c11a80e84a2becf109c4014d7)

