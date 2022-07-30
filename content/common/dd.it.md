---
author: ['Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1617292466
title: "dd"
description: "dd, Converti e copia un file."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/dd>.

- Crea un disco USB avviabile da un file ISO e mostra il progresso:

```bash
dd if=file.iso of=/dev/disco_usb status=progress
```

- Clona un disco in un altro a blocchi di 4MB, ignora gli errori e mostra il progresso:

```bash
dd if=/dev/disco_sorgente of=/dev/disco_destinazione bs=4M conv=noerror status=progress
```

- Genera un file di 100 byte randomici utilizzando il driver random del kernel:

```bash
dd if=/dev/urandom of=file_random bs=100 count=1
```

- Testa la performance in scrittura di un disco:

```bash
dd if=/dev/zero of=file_1GB bs=1024 count=1000000
```

- Mostra il progresso di un'operazione dd in corso (comando da eseguire in un'altra shell):

```bash
kill -USR1 $(pgrep ^dd)
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dd: change more information link (#5548) | 2021-03-30T12:18:12 | [4a95098a45d0](https://github.com/tldr-pages/tldr/commit/4a95098a45d072a9e1204208ff6dff13ae51c693)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | dd: add Italian translation. | 2019-06-10T01:35:02 | [5b2b8c98c499](https://github.com/tldr-pages/tldr/commit/5b2b8c98c4996d1725a73890ca914e329fa00d4d)

