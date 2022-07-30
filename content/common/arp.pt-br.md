---
author: ['FilipaDurao', 'marchersimon']
date: 1618756407
title: "arp"
description: "arp, Mostrar e manipular a cache ARP do sistema."
categories: "common"
---
> Mais informações: <https://manned.org/arp>.

- Mostrar a tabela arp atual:

```bash
arp -a
```

- Limpar toda a cache:

```bash
sudo arp -a -d
```

- Eliminar uma entrada específica:

```bash
arp -d endereço
```

- Criar uma entrada:

```bash
arp -s endereço endereço_mac
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | arp: add pt_BR translation (#3419) | 2019-10-17T14:47:59 | [854ed025b021](https://github.com/tldr-pages/tldr/commit/854ed025b021e4c42594938e46133c29c5de1315)

