---
author: ['Reinhart Previano Koentjoro', 'Desc4rtes']
date: 1641608133
title: "apt, TLDR Pages"
description: "apt, Debian tabanlı dağıtımlar için paket yönetim aracı."
categories: "linux"
---
> Ubuntu 16.04 ve sonraki sürümlerde interaktif kullanıldığında `apt-get` için önerilen değiştirme.

> Daha fazla bilgi: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Kullanılabilir paket ve versiyonların listesini yenile (Bu komutu diğer `apt` komutlarından önce kullanmanız önerilir):

```bash
apt update
```

- Belirli bir paketi arayın:

```bash
apt search paket
```

- Bir paketin bilgilerini gösterin:

```bash
apt show paket
```

- Bir paket kurun veya mevcut en son sürüme güncelleyin:

```bash
apt install paket
```

- Bir paketi kaldırın (bunun için "purge" kullanmak, yapılandırma dosyalarını da kaldırır):

```bash
apt remove paket
```

- Kurulu tüm paketleri mevcut en yeni sürümlerine yükseltin:

```bash
apt upgrade
```

- Tüm paketleri listeleyin:

```bash
apt list
```

- Kurulu paketleri listeleyin:

```bash
apt list --installed
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[Desc4rtes](mailto:cheryyblossom.ai@gmail.com) | apt: add Turkish translation (#7250) | 2021-10-28T05:15:27 | [46f2396f371e](https://github.com/tldr-pages/tldr/commit/46f2396f371eda3bb34944bb51bdbdcb469b5591)

