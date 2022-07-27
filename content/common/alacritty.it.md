---
author: ['gsobell']
date: 1626955901
title: "alacritty, TLDR Pages"
description: "alacritty, Multipiattaforma, GPU-accelerato emulatore di terminale."
categories: "common"
---
> Maggiori informazioni: <https://github.com/alacritty/alacritty>.

- Apri un nuovo finestra di Alacritty:

```bash
alacritty
```

- Esegui in una cartella specifica:

```bash
alacritty --working-directory percorso/a/cartella
```

- Esegui un comando in una nuova finestra di Alacritty:

```bash
alacritty -e comando
```

- Specifica un file di configurazione alternativo (predefinito a `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

```bash
alacritty --config-file path/to/config.yml
```

- Esegui con ricaricamento configurazione live (può anche essere acceso in `alacritty.yml`):

```bash
alacritty --live-config-reload --config-file percorsi/al/config.yml
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

