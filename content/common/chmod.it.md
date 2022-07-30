---
author: ['Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1617292466
title: "chmod"
description: "chmod, Cambia i permessi di accesso di file o directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/chmod>.

- Dai il permesso di eseguire (x) un file al suo proprietario (u):

```bash
chmod u+x percorso/al/file
```

- Dai permessi di lettura (r) e scrittura (w) per un file/directory al suo proprietario:

```bash
chmod u+rw percorso/a/file_o_directory
```

- Rimuovi i permessi di esecuzione al [g]ruppo proprietario del file:

```bash
chmod g-x percorso/al/file
```

- Dai a tutti gli utenti (a) diritti di lettura ed esecuzione:

```bash
chmod a+rx percorso/al/file
```

- Dai ad altri utenti (non nel gruppo proprietario) gli stessi diritti del gruppo:

```bash
chmod o=g percorso/al/file
```

- Cambia permessi ricorsivamente dando al [g]ruppo e agli altri utenti (o) diritto di scrittura:

```bash
chmod -R g+w,o+w percorso/alla/directory
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | chmod: add Italian translation. | 2019-03-03T23:44:18 | [fe91660a337f](https://github.com/tldr-pages/tldr/commit/fe91660a337f01fc7a9490c87fa3a57ee373d0c5)

