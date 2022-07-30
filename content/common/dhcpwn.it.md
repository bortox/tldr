---
author: ['Marco Bonelli']
date: 1560123302
title: "dhcpwn"
description: "dhcpwn, Testa attacchi di esaurimento IP DHCP ed intercetta il traffico DHCP locale."
categories: "common"
---
> Maggiori informazioni: <https://github.com/mschwager/dhcpwn>.

- Inonda la rete con richieste di IP:

```bash
dhcpwn --interface interfaccia flood --count numero_di_richieste
```

- Intercetta traffico DHCP locale:

```bash
dhcpwn --interface interfaccia sniff
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | dhcpwn: add Italian translation. | 2019-06-10T01:35:02 | [05241b45814b](https://github.com/tldr-pages/tldr/commit/05241b45814b6c67553439a4c6c3cfe9c7d67fce)

