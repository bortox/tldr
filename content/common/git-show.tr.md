---
author: ['Tan A', 'lincc']
date: 1643487459
title: "git show"
description: "git show, Çeşitli Git nesnelerini (commit'ler, etiketler vs.) görüntüle."
categories: "common"
---
> Daha fazla bilgi: <https://git-scm.com/docs/git-show>.

- Son commit'e dair bilgi (değer, mesaj, değişimler ve öbür metaveriler) göster:

```bash
git show
```

- Belirtilen commit'e dair bilgi göster:

```bash
git show commit
```

- Belirtilen etiket ile özleşen commit'e dair bilgi göster:

```bash
git show tag
```

- Dalın HEAD'indeki 3. commit'e dair bilgi göster:

```bash
git show dal~3
```

- Commit'in mesajını diff çıktısını önleyerek tek satırda göster:

```bash
git show --oneline -s commit
```

- Yalnızca değiştirilen dosyalarla ilgili istatistik (eklenen/silinen karakterler) göster:

```bash
git show --stat commit
```

- Yalnızca eklenen, yeniden adlandırılan veya silinen dosyaların listesini göster:

```bash
git show --summary commit
```

- Bir dosyanın belirtilen sürümdeki (örneğin dal, etiket veya commit) içeriğini göster:

```bash
git show sürüm:dosya/konumu
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | git*: add Turkish translation (#7581) * translate git.md to tr * translate git-add.md to tr * translate git-am.md to tr * translate [...] | 2021-12-29T13:28:58 | [f9b662115a76](https://github.com/tldr-pages/tldr/commit/f9b662115a765f843982cea237d608aab423e3f7)

