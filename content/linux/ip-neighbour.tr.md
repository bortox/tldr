---
author: ['Oğuz Ersen', 'Raizo62']
date: 1649594825
title: "ip neighbour"
description: "ip neighbour, Komşu/ARP tablosu yönetimi IP alt komutu."
categories: "linux"
---
> Daha fazla bilgi: <https://manned.org/ip-neighbour.8>.

- Komşu/ARP tablosu girdilerini görüntüle:

```bash
ip neighbour
```

- `eth0` aygıtının komşu tablosundaki girdileri kaldır:

```bash
sudo ip neighbour flush dev eth0
```

- Bir komşu araması gerçekleştir ve bir komşu girdisi döndür:

```bash
ip neighbour get aranacak_ip dev eth0
```

- `eth0` arayüzüne komşu IP adresi için bir ARP girdisi ekle veya sil:

```bash
sudo ip neighbour add|del ip_adresi lladdr mac_adresi dev eth0 nud reachable
```

- `eth0` arayüzünde komşu IP adresi için bir ARP girdisini değiştir:

```bash
sudo ip neighbour change|replace ip_adresi lladdr yeni_mac_adresi dev eth0
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Raizo62](mailto:silicium62-github@yahoo.fr) | ip-neighbour.md : title : the command is "ip" and not "ip-neighbour" (#7973) the syntaxof title is now consistent with the others commands | 2022-04-10T14:47:05 | [119c84205ea4](https://github.com/tldr-pages/tldr/commit/119c84205ea469d0ee438fed30a79cf47bb3012d)
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | ip-neighbour: add Turkish translation | 2022-03-09T23:42:24 | [6332954fe3b6](https://github.com/tldr-pages/tldr/commit/6332954fe3b63b65ab1aae2e98e20361cf25b58c)

