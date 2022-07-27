---
author: ['Raffaele Mignone']
date: 1635204663
title: "gocryptfs, TLDR Pages"
description: "gocryptfs, Filesystem crittografato scritto in Go."
categories: "common"
---
> Maggiori informazioni: <https://github.com/rfjakob/gocryptfs>.

- Inizializzare un filesystem crittografato:

```bash
gocryptfs -init percorso/al/cifrata
```

- Montare un filesystem crittografato:

```bash
gocryptfs percorso/cartella/cifrata percorso/punto/di/mount
```

- Montare un filesystem usando la master key invece della password:

```bash
gocryptfs --masterkey percorso/cartella/cifrata percorso/punto/di/mount
```

- Cambiare la password:

```bash
gocryptfs --passwd percorso/cartella/cifrata
```

- Generare uno snapshot cifrato di una cartella:

```bash
gocryptfs --reverse percorso/al/directory percorso/cartella/cifrata
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Raffaele Mignone](mailto:github@norangeb.it) | gocryptfs: add Italian translation (#6993) | 2021-10-26T01:31:03 | [d27c18c592ee](https://github.com/tldr-pages/tldr/commit/d27c18c592ee5a26097565b44c08aa8325967b75)

