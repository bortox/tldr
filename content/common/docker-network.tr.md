---
author: ['lincc', 'Tan A']
date: 1643487459
title: "docker network, TLDR Pages"
description: "docker network, Docker ağları oluştur ve yönet."
categories: "common"
---
> Daha fazla bilgi: <https://docs.docker.com/engine/reference/commandline/network/>.

- docker daemon'daki tüm müsait ve düzenlenmiş ağları sırala:

```bash
docker network ls
```

- Kullanıcı tarafından belirtilmiş bir ağ oluştur:

```bash
docker network create --driver driver_name ağ_ismi
```

- Boşluk ile ayrılmış bir ağ listesinin detaylı bilgisini görüntüle:

```bash
docker network inspect ağ_ismi
```

- Bir konteyneri isim veya ID kullanarak bir ağa bağla:

```bash
docker network connect ağ_ismi konteyner_ismi|ID
```

- Bir konteyneri bir ağdan çıkar:

```bash
docker network disconnect ağ_ismi konteyner_ismi|ID
```

- Tüm kullanılmayan (hiçbir konteyner tarafından belirtilmeyen) ağları sil:

```bash
docker network prune
```

- Kullanılmayan ağların boşluk ile ayrılmış bir listesini sil:

```bash
docker network rm ağ_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | docker-*: add Turkish translations (#5321) | 2021-03-02T12:26:41 | [2609b4b012e3](https://github.com/tldr-pages/tldr/commit/2609b4b012e3a528f8cc86201956fab27c7f72b2)

