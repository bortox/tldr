---
author: ['gsobell']
date: 1626955901
title: "colordiff"
description: "colordiff, Un'utilità per aggiungere colore all'output diff."
categories: "common"
---
> colordiff è un wrapper scritto in Perl per `diff` e produce lo stesso output, ma con una bella evidenziazione della sintassi. I colori possono essere personalizzati.

> Maggiori informazioni: <https://github.com/kimmel/colordiff>.

- Analisi di due file:

```bash
colordiff file1 file2
```

- Output in due colonne:

```bash
colordiff -y file1 file2
```

- Ignora differenze di maiuscole in file:

```bash
colordiff -i file1 file2
```

- Notifica se file identici:

```bash
colordiff -s file1 file2
```

- Ignora spazio vuoto (white space):

```bash
colordiff -w file1 file2
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

