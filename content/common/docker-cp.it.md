---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker cp, TLDR Pages"
description: "docker cp, Copia file o directory tra il filesystem di un container e quello locale (host)."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/cp>.

- Copia un file o una directory dall'host a un container:

```bash
docker cp percorso/al/file_o_directory_su_host nome_container:percorso/al/file_o_directory_su_container
```

- Copia un file o una directory da un container all'host:

```bash
docker cp nome_container:percorso/al/file_o_directory_su_container percorso/al/file_o_directory_su_host
```

- Copia un file o una directory dall'host a un container, seguendo un link simbolico (non copiare il link simbolico, ma direttamente il file da lui referenziato):

```bash
docker cp --follow-link percorso/al/link_simbolico_su_host nome_container:percorso/al/file_o_directory_su_container
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

