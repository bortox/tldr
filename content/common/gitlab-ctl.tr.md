---
author: ['lincc', 'Tan A']
date: 1643487459
title: "gitlab-ctl, TLDR Pages"
description: "gitlab-ctl, Çok amaçlı GitLab yönetim CLI aracı."
categories: "common"
---
> Daha fazla bilgi: <https://docs.gitlab.com/omnibus/maintenance/>.

- Tüm servislerin durumunu görüntüle:

```bash
sudo gitlab-ctl status
```

- Belirtilen servisin durumunu görüntüle:

```bash
sudo gitlab-ctl status nginx
```

- Tüm servisleri yeniden başlat:

```bash
sudo gitlab-ctl restart
```

- Belirtilen servisi yeniden başlat:

```bash
sudo gitlab-ctl restart nginx
```

- Tüm servislerin kaydını görüntüle ve `Ctrl + C` basılana kadar okumaya devam et:

```bash
sudo gitlab-ctl tail
```

- Belirtilen servisin kaydını görüntüle:

```bash
sudo gitlab-ctl tail nginx
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)

