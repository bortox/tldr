---
author: ['Marco Bonelli']
date: 1560123302
title: "clamscan"
description: "clamscan, Scanner antivirus da linea di comando."
categories: "common"
---
> Maggiori informazioni: <https://www.clamav.net>.

- Analizza un file cercando vulnerabilità:

```bash
clamscan percorso/al/file
```

- Analizza ricorsivamente tutti i file in una specifica directory:

```bash
clamscan -r percorso/alla/directory
```

- Analizza dati da standard input:

```bash
comando | clamscan -
```

- Specifica un file o directory di file da usare come database virus:

```bash
clamscan --database percorso/a/file_o_directory
```

- Analizza la directory corrente e mostra in output solo i file infetti:

```bash
clamscan --infected
```

- Scrivi il risultato di uno scan in un file di log:

```bash
clamscan --log percorso/a/file_log
```

- Sposta i file infetti in una specifica directory:

```bash
clamscan --move percorso/a/directory_quarantena
```

- Elimina i file infetti:

```bash
clamscan --remove yes
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | clamscan: add Italian translation. | 2019-06-10T01:35:02 | [ef9ff46b9f02](https://github.com/tldr-pages/tldr/commit/ef9ff46b9f021d93ca18a0fcd52605a1d6d46659)

