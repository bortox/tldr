---
author: ['marchersimon', 'lincc']
date: 1643487459
title: "tree, TLDR Pages"
description: "tree, Mevcut dizinin içeriğini ağaç biçiminde göster."
categories: "common"
---
> Daha fazla bilgi: <http://mama.indstate.edu/users/ice/tree/>.

- Dosya ve dizinleri `num` değeri kadar derinlikte göster (1 olması durumunda mevcut dizin gösterilir):

```bash
tree -L num
```

- Yalnızca dizinleri göster:

```bash
tree -d
```

- Renklendirme açık olacak şekilde gizli dosyaları dahi göster:

```bash
tree -a -C
```

- Ağacın satırlarını girintiler yerine tüm yolu belirterek göster:

```bash
tree -i -f
```

- Tüm dosyaların ve dizinlerin eklenerek artan boyutlarını, insanların okuyabileceği bir biçimde göster:

```bash
tree -s -h --du
```

- Ağaç hiyerarşisi içindeki dosyaları bir wildcard (glob) kalıbı kullanarak ve aranan özellikteki dosyalara sahip olmayan dizinleri yoksayarak göster:

```bash
tree -P '*.txt' --prune
```

- Ağaç hiyerarşisi içindeki dizinleri bir wildcard (glob) kalıbı kullanarak ve istenen dizine atalığı olmayan dizinleri yoksayarak göster:

```bash
tree -P dizin_ismi --matchdirs --prune
```

- Ağacı belirtilen dizinleri yoksayarak göster:

```bash
tree -I 'dizin_ismi1|dizin_ismi2'
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

