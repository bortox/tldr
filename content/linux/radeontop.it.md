---
author: ['gsobell']
date: 1626955901
title: "radeontop"
description: "radeontop, Mostra Utilizzo di AMD GPUs."
categories: "linux"
---
> Maggiori informazioni: <https://github.com/clbr/radeontop>.

- Mostra utilizzo del AMD GPU principale:

```bash
sudo radeontop
```

- Inizia output con colore:

```bash
sudo radeontop --colour
```

- Scegli un GPU specifico (il numero del bus è il primo numero nell'output di `lspci`):

```bash
sudo radeontop --bus bus_numero
```

- Specifica la frequenza di aggiornamento del display (più alto aggiunge più sovraccarico al GPU):

```bash
sudo radeontop --ticks aggiornamenti_per_secondo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

