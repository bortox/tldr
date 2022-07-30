---
author: ['Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1559564381
title: "ansible-playbook"
description: "ansible-playbook, Esegui task definiti nel playbook di un computer remoto via SSH."
categories: "common"
---
> Maggiori informazioni: <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- Esegui tasks nel playbook:

```bash
ansible-playbook playbook
```

- Esegui task nel playbook con un inventory personalizzato:

```bash
ansible-playbook playbook -i inventory
```

- Esegui task nel playvook con variabili aggiuntive definite da linea di comando:

```bash
ansible-playbook playbook -e "variabile1=valore1 variabile2=valore2 ..."
```

- Esegui task nel playbook con variabili aggiuntive definite in un file JSON:

```bash
ansible-playbook playbook -e "@variabili.json"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | ansible-playbook.md:fix style | 2019-05-14T19:40:23 | [157f72c44c4c](https://github.com/tldr-pages/tldr/commit/157f72c44c4c39fadee3c7dcae4ab6dc745dc8d3)
[Schneider](mailto:lucas.schneider@sap.com) | it\ansible-playbook.md: add homepage | 2019-05-14T19:40:23 | [930fe441dd3b](https://github.com/tldr-pages/tldr/commit/930fe441dd3b8c0e981cd768ff09617389d31bb5)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

