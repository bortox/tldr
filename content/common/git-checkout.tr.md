---
author: ['lincc', 'Tan A']
date: 1643487459
title: "git checkout, TLDR Pages"
description: "git checkout, Bulunulan dalı değiştir veya çalışma ağaçlarını onar."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-checkout>.

- Yeni bir dal oluştur ve bu dala geç:

```bash
git checkout -b dal_ismi
```

- Belirtilen bir referansa (dal, uzak/dal, etiket gibi) dayanacak şekilde yeni bir dal oluştur ve bu dala geç:

```bash
git checkout -b dal_ismi referans
```

- Varolan yerel bir dala geç:

```bash
git checkout dal_ismi
```

- En son kontrol edilmiş olan dala geç:

```bash
git checkout -
```

- Uzak bağlantıdaki varolan bir dala geç:

```bash
git checkout --track uzak_bağlantı_adresi/dal_ismi
```

- Mevcut dizindeki sahnelenmemiş tüm değişiklikleri ayır (geri alma benzeri bir komut için `git reset` komutu önerilir):

```bash
git checkout .
```

- Sahnelenmemiş değişiklikleri belirtilen dosyaya ayır:

```bash
git checkout dosya_ismi
```

- Mevcut dizindeki bir dosyayı, belirtilen dalda commit edilmiş sürümü ile değiştirin:

```bash
git checkout dal_ismi -- dosya_ismi
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

