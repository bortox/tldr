---
author: ['Oğuz Ersen']
date: 1647493732
title: "dnf"
description: "dnf, RHEL, Fedora ve CentOS için paket yönetim aracı (yum'un yerini alır)."
categories: "linux"
---
> Daha fazla bilgi: <https://dnf.readthedocs.io>.

- Kurulu paketleri kullanılabilir en yeni sürümlere yükselt:

```bash
sudo dnf upgrade
```

- Anahtar kelimeler kullanarak paket ara:

```bash
dnf search anahtar_kelimeler
```

- Bir paketin ayrıntılarını göster:

```bash
dnf info paket
```

- Yeni bir paket kur:

```bash
sudo dnf install paket
```

- Yeni bir paket kur ve tüm soruları otomatik evet olarak yanıtla:

```bash
sudo dnf -y install paket
```

- Bir paketi kaldır:

```bash
sudo dnf remove paket
```

- Kurulu paketleri listele:

```bash
dnf list --installed
```

- Verilen dosyayı hangi paketlerin sağladığını bul:

```bash
dnf provides dosya
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | atool, dnf, wl-copy, wl-paste: add Turkish translation (#7837) * wl-copy, wl-paste: fix invalid command options --paste-once is valid [...] | 2022-03-17T06:08:52 | [e7a06bac2805](https://github.com/tldr-pages/tldr/commit/e7a06bac28057862cb80128905031eab5173ff0b)

