---
author: ['Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'franzqat', 'Franz']
date: 1633438869
title: "ansible"
description: "ansible, Gestisce gruppi di computer da remoto via SSH."
categories: "common"
---
> Usa il file `/etc/ansible/hosts` per aggiungere nuovi gruppi/host.

> Alcuni comandi aggiuntivi, come `ansible galaxy`, hanno la propria documentazione.

> Maggiori informazioni: <https://www.ansible.com/>.

- Elenca gli host appartenenti ad un gruppo:

```bash
ansible gruppo --list-hosts
```

- Invia un ping ad un gruppo di host invocando il modulo "ping":

```bash
ansible gruppo -m ping
```

- Mostra informazioni su un gruppo di host invocando il modulo "setup":

```bash
ansible gruppo -m setup
```

- Esegui un comando su un gruppo di host invocando il modulo "command" con degli argomenti:

```bash
ansible gruppo -m command -a 'comando_da_eseguire'
```

- Esegui un comando con privilegi di amministratore:

```bash
ansible gruppo --become --ask-become-pass -m command -a 'comando'
```

- Esegui un comando usando un file di inventory personalizzato:

```bash
ansible gruppo -i file_inventory -m command -a 'comando'
```

- Elenca i gruppi in un inventory:

```bash
ansible localhost -m debug -a 'var=groups.keys()'
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[franzqat](mailto:franz.f1032@gmail.com) | ansible: sync Italian translation (#6780) | 2021-10-04T18:08:26 | [a813813fe35f](https://github.com/tldr-pages/tldr/commit/a813813fe35f5674ee9277d4c85d448a19832fe1)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\ansible.md: add homepage | 2019-05-14T19:40:23 | [bfae6f26d249](https://github.com/tldr-pages/tldr/commit/bfae6f26d24951e2790d76a5350a02beccebc76c)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

