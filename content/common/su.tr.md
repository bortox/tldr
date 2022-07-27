---
author: ['Azrael JD', 'Desc4rtes']
date: 1643125837
title: "su, TLDR Pages"
description: "su, Kabuk ortamında başka bir kullanıcıya geçiş yapın."
categories: "common"
---
> Daha fazla bilgi: <https://manned.org/su>.

- Süper kullanıcıya geçin (kök şifresi gerektirir):

```bash
su
```

- Belirli bir kullanıcıya geçin (kullanıcının şifresini gerektirir):

```bash
su kullanıcıadı
```

- Belirli bir kullanıcıya geçin ve tam oturum açma kabuğunu simüle edin:

```bash
su - kullanıcıadı
```

- Başka bir kullanıcı olarak bir komut çalıştırın:

```bash
su - kullanıcıadı -c "komut"
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | su: add more information link (#7705) | 2022-01-25T16:50:37 | [5b28d44739a4](https://github.com/tldr-pages/tldr/commit/5b28d44739a43a6e8ff073ce6de1ecc89d8dd7b3)
[Desc4rtes](mailto:cheryyblossom.ai@gmail.com) | su: add Turkish translation (#7268) | 2021-10-29T11:31:39 | [99daa782c560](https://github.com/tldr-pages/tldr/commit/99daa782c560140a6ba16e1f98d36dfd91c5437e)

