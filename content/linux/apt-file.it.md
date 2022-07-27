---
author: ['Patrice Denis', 'Agno94']
date: 1618665963
title: "apt-file, TLDR Pages"
description: "apt-file, Cerca un file dentro un pacchetto apt, includendo quelli non ancora installati."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Aggiorna il database dei metadati:

```bash
sudo apt update
```

- Cerca i pacchetti che contengono un file o un percorso specificato:

```bash
apt-file search parte/del/filename
```

- Elenca i contenuti di un pacchetto specifico:

```bash
apt-file list nome_del_pacchetto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

