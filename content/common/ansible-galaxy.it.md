---
author: ['Schneider', 'Franz', 'Marco Bonelli']
date: 1633745403
title: "ansible-galaxy"
description: "ansible-galaxy, Crea e gestisci ruoli di Ansible."
categories: "common"
---
> Maggiori informazioni: <https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html>.

- Installa un ruolo:

```bash
ansible-galaxy install utente.ruolo
```

- Rimuovi un ruolo:

```bash
ansible-galaxy remove utente.ruolo
```

- Elenca i ruoli installati:

```bash
ansible-galaxy list
```

- Cerca un determinato ruolo:

```bash
ansible-galaxy search nome_ruolo
```

- Crea un nuovo ruolo:

```bash
ansible-galaxy init nome_nuovo_ruolo
```

- Acquisisci informazioni su un ruolo di un utente:

```bash
ansible-galaxy role info nome_utente.nome_ruolo
```

- Acquisisci informazioni su una collection:

```bash
ansible-galaxy collection info nome_utente.nome_raccolta
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | ansible-galaxy: sync Italian translation (#6781) | 2021-10-09T04:10:03 | [51f68b0fb6e1](https://github.com/tldr-pages/tldr/commit/51f68b0fb6e123ab029fef790dc9ea241a52b29b)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\ansible-galaxy.md:add homepage | 2019-05-14T19:40:23 | [99fed4a9ea77](https://github.com/tldr-pages/tldr/commit/99fed4a9ea77afb2cca94edd66aa6d111fde02dc)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

