---
author: ['Luca Lumetti', 'syleung']
date: 1633350747
title: "xxd, TLDR Pages"
description: "xxd, Mostra la rappresentazione esadecimale (hexdump) di un file binario e viceversa."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/xxd>.

- Creare l'hexdump di un file binario e mostrare l'output:

```bash
xxd file_di_input
```

- Creare l'hexdump di un file binario e salvare il risultato in un file:

```bash
xxd file_di_input file_di_output
```

- Mostrare un output in una versione un po' più compatta, dove gli zero consegutivi vengono sostituiti da un asterisco.

```bash
xxd -a file_di_input
```

- Mostrare l'output in 10 colonne di un ottetto (byte) ciascuna:

```bash
xxd -c 10 file_di_input
```

- Mostrare l'output solo fino ad una lunghezza massima di 32 bytes:

```bash
xxd -l 32 file_di_input
```

- Mostrare l'output in modalità normale, senza spazi tra le colonne:

```bash
xxd -p file_di_input
```

- Eseguire l'operazione inversa, ovvero da un hexdump creare il binario e salvarlo in un file:

```bash
xxd -r -p file_di_input file_di_output
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/x*: add more information link (#6664) | 2021-10-04T14:32:27 | [99a72c556f56](https://github.com/tldr-pages/tldr/commit/99a72c556f563a928a10ff2c2146ad42d9af2990)
[Luca Lumetti](mailto:lumetti.luca@gmail.com) | xkill, xxd, nvim: add italian translation (#5862) | 2021-05-01T20:29:19 | [9ccc49d98f38](https://github.com/tldr-pages/tldr/commit/9ccc49d98f381d0a97e1cef45eb7e3e2c883a97a)

