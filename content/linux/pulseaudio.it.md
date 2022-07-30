---
author: ['Triad']
date: 1635956153
title: "pulseaudio"
description: "pulseaudio, Programma che permette di gestire il daemon audio di sistema."
categories: "linux"
---
> Maggiori informazioni: <https://www.freedesktop.org/wiki/Software/PulseAudio/>.

- Controlla se PulseAudio è in esecuzione. Se il programma non è attivo viene restituito un exit code diverso da 0:

```bash
pulseaudio --check
```

- Esegue il daemon di PulseAudio in background:

```bash
pulseaudio --start
```

- Interrompe l'esecuzione del daemon di PulseAudio:

```bash
pulseaudio --kill
```

- Mostra i moduli disponibili:

```bash
pulseaudio --dump-modules
```

- Carica un modulo all'interno del daemon in esecuzione con gli argomenti specificati:

```bash
pulseaudio --load="nome_modulo argomenti"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Triad](mailto:33317323+MrTriad@users.noreply.github.com) | pulseaudio: add Italian translation (#7351) | 2021-11-03T17:15:53 | [c5d01d70f5d5](https://github.com/tldr-pages/tldr/commit/c5d01d70f5d5085515b7776e5cf9977d027fb661)

