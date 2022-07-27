---
author: ['lincc', 'Tan A']
date: 1643487459
title: "cmake, TLDR Pages"
description: "cmake, Çok platformlu yapım sistem oluşturucusu."
categories: "common"
---
> Hedeflenen sisteme göre Makefile, Visual Studio projeleri ve benzerlerini oluşturur.

> Daha fazla bilgi: <https://cmake.org/cmake/help/latest/manual/cmake.1.html>.

- Bir Makefile oluştur ve onu aynı dizindeki bir projeyi derlemek için kullan:

```bash
cmake && make
```

- Bir Makefile oluştur ve onu farklı bir "yapim" dizinindeki projeyi derlemek için kullan (kaynak-dışı yapım):

```bash
cmake -H. -B build && make -C yapim
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | chroot, cmake: add Turkish translation (#5173) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-23T21:36:23 | [3a1609b196d6](https://github.com/tldr-pages/tldr/commit/3a1609b196d6a04109750f124e1fa1ff4f0560e1)

