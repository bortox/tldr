---
author: ['MeerBiene', 'Daniel', 'lincc']
date: 1643487459
title: "apt-key"
description: "apt-key, Schlüssel Management Tool für den APT Paket Manager auf Debian und Ubuntu."
categories: "linux"
---
> Notiz: `apt-key` ist deprecated (außer für `apt-key del` in Maintainer Scripts).

> Weitere Informationen: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Liste alle vertrauten Schlüssel auf:

```bash
apt-key list
```

- Füge einen Schlüssel hinzu:

```bash
apt-key add public_key_file.asc
```

- Lösche einen Schlüssel:

```bash
apt-key del key_id
```

- Füge einen Remote Schlüssel hinzu:

```bash
wget -qO - https://host.tld/filename.key | apt-key add -
```

- Füge einen Schlüssel von einem Schlüsselserver hinzu nur mit der Schlüssel ID:

```bash
apt-key adv --keyserver pgp.mit.edu --recv KEYID
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

