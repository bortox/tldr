---
author: ['Andrea', 'Patrice Denis']
date: 1618661981
title: "adduser"
description: "adduser, Servizio per aggiungere utenti."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/adduser/adduser.html>.

- Crea un nuovo utente con una home directory predefinita e richiede all'utente di impostare una password:

```bash
adduser nome_utente
```

- Crea un utente senza una home directory:

```bash
adduser --no-create-home nome_utente
```

- Crea un utente con una home directory nel percorso specificato:

```bash
adduser --home percorso/all/home nome_utente
```

- Crea un nuovo utente con l'interprete di comandi(shell) specificato come shell di accesso:

```bash
adduser --shell percorso/alla/shell nome_utente
```

- Crea un nuovo utente appartenente al gruppo specificato:

```bash
adduser --ingroup gruppo nome_utente
```

- Aggiunge un utente esistente al gruppo specificato:

```bash
adduser nome_utente gruppo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

