---
author: ['Seifer23']
date: 1644117941
title: "ac"
description: "ac, Imprimeix estadístiques sonre el temps de connexió dels usuaris."
categories: "linux"
---
> Més informació: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Imprimeix el temps de connexió del usuari actual en hores:

```bash
ac
```

- Imprimeix el temps total de connexió de tots els usuaris en hores:

```bash
ac --individual-totals
```

- Imprimeix el temps total de connexió d'un usuari concret en hores:

```bash
ac --individual-totals nom_usuari
```

- Imprimeix el temps de connexió d'un usuari concret en hores per dia (amb total):

```bash
ac --daily-totals --individual-totals nom_usuari
```

- Mostra també detalls adicionals:

```bash
ac --compatibility
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

