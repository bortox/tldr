---
author: ['Carlo Federico Vescovo', 'Lucas Gabriel Schneider', 'Kyle']
date: 1629747204
title: "as, TLDR Pages"
description: "as, Assembler GNU portabile."
categories: "osx"
---
> Progettato principalmente per assemblare l'output di `gcc` ed utilizzarlo con `ld`.

> Maggiori informazioni: <https://www.unix.com/man-page/osx/1/as/>.

- Assembla un file, scrivendo l'output su a.out:

```bash
as file.s
```

- Assembla l'output nel file dato:

```bash
as file.s -o out.o
```

- Genera l'output più velocemente saltando gli spazi e senza preprocessare i commenti. (Questo comando dovrebbe essere utilizzato solo con compilatori fidati):

```bash
as -f file.s
```

- Includi un percorso dato alla lista delle cartelle in cui cercare i file specificati nelle direttive `.include`:

```bash
as -I path/to/directory file.s
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Carlo Federico Vescovo](mailto:vescovocarlofederico@gmail.com) | apachectl, archey, as: add Italian translation (#4450) | 2020-10-05T16:35:15 | [1e596608da3b](https://github.com/tldr-pages/tldr/commit/1e596608da3b073858ba6df5acd47a7ea1e89118)

