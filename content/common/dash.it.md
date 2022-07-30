---
author: ['gsobell']
date: 1626955901
title: "dash"
description: "dash, Debian Almquist Shell, una implementazione di `sh` moderna, che conforme a POSIX, (non compatibile con Bash)."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/dash>.

- Avvia una sessione shell interattiva:

```bash
dash
```

- Esegui un comando, ed esci subito:

```bash
dash -c "comando"
```

- Esegui un script:

```bash
dash percorso/allo/script.sh
```

- Esegui comandi da un script, stampando ogni comando prima di eseguirlo:

```bash
dash -x percorso/allo/script.sh
```

- Esegui comandi da un script, fermandosi al primo errore:

```bash
dash -e percorso/allo/script.sh
```

- Leggi ed esegui commandi dal stdin:

```bash
dash -s
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

