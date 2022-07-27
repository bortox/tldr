---
author: ['cyqsimon']
date: 1639653526
title: "chcon, TLDR Pages"
description: "chcon, Cambia contesto di sicurezza SELinux di file o directory."
categories: "linux"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/chcon>.

- Mostra il contesto di sicurezza di un file:

```bash
ls -lZ percorso/al/file
```

- Cambia il contesto di sicurezza di un file usandone un'altro come riferimento:

```bash
chcon --reference=file_di_riferimento file
```

- Cambia l'intero contesto di sicurezza SELinux di un file:

```bash
chcon utente:ruolo:tipo:range/livello file
```

- Cambia solo l'utente di un contesto di sicurezza SELinux:

```bash
chcon -u utente file
```

- Cambia solo il ruolo di un contesto di sicurezza SELinux:

```bash
chcon -r ruolo file
```

- Cambia solo il tipo di un contesto di sicurezza SELinux:

```bash
chcon -t tipo file
```

- Cambia solo il range/livello di un contesto di sicurezza SELinux:

```bash
chcon -l range/livello file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[cyqsimon](mailto:28627918+cyqsimon@users.noreply.github.com) | chcon: move from common to linux platform (#7544) | 2021-12-16T12:18:46 | [df0117359b09](https://github.com/tldr-pages/tldr/commit/df0117359b099af835e8d16c88ff631b7e71f804)

