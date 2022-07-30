---
author: ['Dario Vladović', 'gRastello', 'marchersimon']
date: 1622748014
title: "ln"
description: "ln, Crea un collegamento a un file o a una directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/ln>.

- Crea un collegamento simbolico a un file (o directory):

```bash
ln -s /percorso/al/file percorso/al/collegamento
```

- Sovrascrivi un collegamento esistente in modo che punti a un nuovo file:

```bash
ln -sf /percorso/al/nuovo/file percorso/al/collegamento
```

- Crea un collegamento fisico a un file:

```bash
ln /percorso/al/file percorso/al/collegamento
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ln: fix typo in flag of Italian page Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2021-06-03T21:20:14 | [61cc8ff0edb4](https://github.com/tldr-pages/tldr/commit/61cc8ff0edb43fbaff4e60ff4cfa676b5eed4408)
[marchersimon](mailto:marchersimon@zohomail.eu) | ln: convert paths to absolute | 2021-06-03T21:20:14 | [0deb4d0597d4](https://github.com/tldr-pages/tldr/commit/0deb4d0597d4eab6abd597fb83e20eb396cf1435)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ln: add more information link (#5560) | 2021-03-30T12:33:54 | [cd1189ec96ca](https://github.com/tldr-pages/tldr/commit/cd1189ec96caf2faa1056e696b0375f341999629)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | ln: add Italian translation. fixed typos added newline | 2019-02-06T17:08:07 | [79702d1138f8](https://github.com/tldr-pages/tldr/commit/79702d1138f8490722c1b899ed63a1e3ddf227d3)

