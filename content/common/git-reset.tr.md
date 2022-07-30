---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git reset"
description: "git reset, Mevcut Git HEAD'ini belirtilen duruma sıfırlayarak commit'leri veya değişiklikleri geri al."
categories: "common"
---
> Eğer bir konum verildiye o konumdaki değişiklikler "geri alınır"; eğer bir commit değeri veya dal verildiyse o commit/dal "geri alınır".

> Daha fazla bilgi: <https://git-scm.com/docs/git-reset>.

- Her şeyi geri al:

```bash
git reset
```

- Belirtilen dosya(lar)ı geri al:

```bash
git reset dosya(ların)/konumu
```

- Bir dosyanın kısımlarını geri al::

```bash
git reset -p dosya/konumu
```

- Son commit'i, dosya sisteminde yapılan değişiklikleri geri almadan geri al:

```bash
git reset HEAD~
```

- Son iki commit'i onların indeks'e yaptığı değişiklikleri ekleyerek geri al:

```bash
git reset --soft HEAD~2
```

- Commit'lenmemiş değişiklikleri sahnelenip sahnelenmediklerine bakmaksızın iptal et (sadece sahnelenmemiş değişiklikleri iptal etmek için `git checkout` kullanılır):

```bash
git reset --hard
```

- Depoyu belirtilen commit'e o zamana kadar yapılan değişiklikleri iptal ederek sıfırla:

```bash
git reset --hard commit
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

