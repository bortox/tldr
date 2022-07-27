---
author: ['lincc', 'Tan A']
date: 1643487459
title: "gitlab-runner, TLDR Pages"
description: "gitlab-runner, GitLab koşucuları için CLI aracı."
categories: "common"
---
> Daha fazla bilgi: <https://docs.gitlab.com/runner/>.

- Bir koşucuyu kayıt ettir:

```bash
sudo gitlab-runner register --url https://gitlab.ornek.com --registration-token token --name isim
```

- Bir koşucuyu Docker çalıştırıcısıyla kayı ettir:

```bash
sudo gitlab-runner register --url https://gitlab.ornek.com --registration-token token --name isim --executor docker
```

- Bir koşucunun kaydını geri al:

```bash
sudo gitlab-runner unregister --name isim
```

- Koşucu servisinin durumunu görüntüle:

```bash
sudo gitlab-runner status
```

- Koşucu servisini yeniden başlat:

```bash
sudo gitlab-runner restart
```

- Kayıt edilen koşucuların GitLab'e bağlanabilme durumlarını kontrol et:

```bash
sudo gitlab-runner verify
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation II (#7589) | 2021-12-30T02:33:18 | [a0ae1f61aff2](https://github.com/tldr-pages/tldr/commit/a0ae1f61aff2917b94779cd03ec1395073f91c56)

