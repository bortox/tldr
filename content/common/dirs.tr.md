---
author: ['marchersimon', 'Tan A', 'lincc']
date: 1643487459
title: "dirs"
description: "dirs, Dizin yığını görüntüler veya üzerinde oynama yapar."
categories: "common"
---
> Dizin yığını, `pushd` ve `popd` komutlarıyla üzerinde oynama yapılabilen, son ziyaret edilen dizinleri gösteren bir listedir.

> Daha fazla bilgi: <https://www.gnu.org/software/bash/manual/bash.html#Directory-Stack-Builtins>.

- Dizin yığınını her madde arasında boşluk olacak şekilde görüntüle:

```bash
dirs
```

- Dizin yığınını her satır başı tek madde olacak şekilde görüntüle:

```bash
dirs -p
```

- Dizin yığınında 0'dan başlamak üzere yalnızca nth girişini göster:

```bash
dirs +N
```

- Dizin yığınını temizle:

```bash
dirs -c
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirs: edit link Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-20T00:05:51 | [5d2fa2261db4](https://github.com/tldr-pages/tldr/commit/5d2fa2261db4d26e09c26f72f35d52e35dcf1bec)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | dirname, dirs, dirsearch: add Turkish translation (#5320) | 2021-03-07T00:09:27 | [ed353b068bab](https://github.com/tldr-pages/tldr/commit/ed353b068bab960c11a80e84a2becf109c4014d7)

