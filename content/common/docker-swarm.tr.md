---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker swarm, TLDR Pages"
description: "docker swarm, Bir konteyner orkestrasyon aracı."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/swarm/>.

- Bir bataklık dizisi oluştur:

```bash
docker swarm init
```

- Bir yönetici veya işçiye takılmak için token göster:

```bash
docker swarm join-token işçi|yönetici
```

- Diziye yeni bir düğüm ekle:

```bash
docker swarm join --token token manager_node_url:2377
```

- Bir işçiyi bataklıktan sil (işçi düğümünün içinde çalıştır):

```bash
docker swarm leave
```

- Mevcut CA sertifikasını PEM formatında görüntüle:

```bash
docker swarm ca
```

- Mevcut CA sertifikasını döndür ve yeni sertifikayı görüntüle:

```bash
docker swarm ca --rotate
```

- Düğüm sertifikaları için geçerli periyodu değiştir:

```bash
docker swarm update --cert-expiry saathdakikamsaniyes
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

