---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "apg"
description: "apg, Crea password randomiche arbitrariamente complesse."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/apg>.

- Genera password randomiche (la lunghezza predefinita è 8):

```bash
apg
```

- Crea una password con almeno 1 simbolo (S), 1 numero (N), 1 lettera maiuscola (C) e una minuscola (L):

```bash
apg -M SNCL
```

- Crea una password di 16 caratteri:

```bash
apg -m 16
```

- Crea una password di massimo 16 caratteri:

```bash
apg -x 16
```

- Crea una password che non è già presente in un dizionario (file dizionario fornito come argomento):

```bash
apg -r dizionario
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: bl-ue <54780737+bl- [...] | 2021-04-18T16:33:27 | [a8cbf084db1c](https://github.com/tldr-pages/tldr/commit/a8cbf084db1c27995da74db5833681eaea87dbfb)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: edit link | 2021-04-18T16:33:27 | [ec6a3682f0fe](https://github.com/tldr-pages/tldr/commit/ec6a3682f0feaea05c28b65ddac54d395b32a284)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: add link | 2021-04-18T16:33:27 | [d5cbcd6fbca3](https://github.com/tldr-pages/tldr/commit/d5cbcd6fbca3201f690a82f177faf6679349e803)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | apd: add Italian translation. | 2019-01-28T19:10:19 | [3d7b1aaa36db](https://github.com/tldr-pages/tldr/commit/3d7b1aaa36dbd4b7c38c634a257beaf415244b3b)

