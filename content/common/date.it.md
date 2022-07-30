---
author: ['Dario Vladović', 'Marco Bonelli', 'Mikey Garcia', 'bl-ue', 'marchersimon']
date: 1621528570
title: "date"
description: "date, Imposta o mostra data e ora di sistema."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/date>.

- Mostra la data corrente utilizzando il formato predefinito della locale corrente:

```bash
date +"%c"
```

- Mostra la data corrente in UTC e formato ISO 8601:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- Mostra la data corrente come timestamp Unix (secondi dall'epoca Unix):

```bash
date +%s
```

- Mostra una specifica data (rappresentata come timestamp Unix) utilizzando il formato predefinito:

```bash
date -d @1473305798
```

- Converti una specifica data in un timestamp Unix:

```bash
date -d "2018-09-01 00:00" +%s --utc
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Revert "date: fix typo (#4069)" (#5997) | 2021-05-20T18:36:10 | [33b5fcd7bdc9](https://github.com/tldr-pages/tldr/commit/33b5fcd7bdc9e3e169e3a3c5c8b767dcb05b770e)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | date: add more information link (#5603) | 2021-03-30T15:50:57 | [b98c0e84a5b2](https://github.com/tldr-pages/tldr/commit/b98c0e84a5b2228add4fe1831fd2eb151c14bca1)
[Mikey Garcia](mailto:gikeymarcia@gmail.com) | date: fix typo (#4069) | 2020-05-27T05:46:20 | [e0151803205b](https://github.com/tldr-pages/tldr/commit/e0151803205bb7efa1e2222a979580dbcfc19589)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | date: add Italian translation. | 2019-06-10T01:35:02 | [aa6bb8a2fa9c](https://github.com/tldr-pages/tldr/commit/aa6bb8a2fa9cea30f2a73a21d1d933666a383cb4)

