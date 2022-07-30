---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git switch"
description: "git switch, Git dalları arasında geçiş yap. Gir sürümü 2.23+ olmalıdır."
categories: "common"
---
> Ayrıca benzer işlev gören `git checkout` komutuna bakılması önerilir.

> Daha fazla bilgi: <https://git-scm.com/docs/git-switch>.

- Varolan bir dala geç:

```bash
git switch dal_ismi
```

- Yeni bir dal yarat ve ona geç:

```bash
git switch --create dal_ismi
```

- Varolan commit üzerine yeni bir dal yarat ve ona geç:

```bash
git switch --create dal_ismi commit
```

- Önceki dala geç:

```bash
git switch -
```

- Bir dala geç ve tüm alt modülleri uyum için güncelle:

```bash
git switch --recurse-submodules dal_ismi
```

- Bir dala geç ve mevcut dal ile commit'lenmeyen değişiklikleri bu dal ile birleştir:

```bash
git switch --merge dal_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

