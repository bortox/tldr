---
author: ['Desc4rtes']
date: 1635499952
title: "date"
description: "date, Sistem tarihini görüntüleyin veya ayarlayın."
categories: "common"
---
> Daha fazla bilgi: <https://www.gnu.org/software/coreutils/date>.

- Varsayılan yerel biçimi kullanarak geçerli tarihi görüntüleyin:

```bash
date +"%c"
```

- Geçerli tarihi UTC ve ISO 8601 formatında görüntüleyin:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- Geçerli tarihi bir Unix zaman damgası olarak görüntüleyin (Unix zamanından bu yana geçen saniyeler):

```bash
date +%s
```

- Varsayılan biçimi kullanarak belirli bir tarihi (Unix zaman damgası olarak) görüntüleyin:

```bash
date -d @1473305798
```

- Belirli bir tarihi Unix zaman damgası biçimine dönüştürün:

```bash
date -d "2018-09-01 00:00" +%s --utc
```

- RFC-3339 biçimini kullanarak geçerli tarihi görüntüleyin (`YYYY-AA-GG ss:dd:ss ZD`):

```bash
date --rfc-3339=s
```
Bu belgede yapılan değişikliklerin listesi


Yazar | Açıklama | ISO 8601 tarih biçimi | GitHuba bağlantı
------|-----|-----|-----
[Desc4rtes](mailto:cheryyblossom.ai@gmail.com) | date: add Turkish translation (#7266) | 2021-10-29T11:32:32 | [963c940bfd8d](https://github.com/tldr-pages/tldr/commit/963c940bfd8ddfbc4b86e21ee5060098a4159549)

