---
author: ['gsobell']
date: 1626955901
title: "ufw"
description: "ufw, ufw (Uncomplicated Firewall) - Firewall Semplice."
categories: "linux"
---
> Frontend per iptables per semplificare la configurazione di un firewall.

> Maggiori informazioni: <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- Accendi ufw:

```bash
ufw enable
```

- Spegni ufw:

```bash
ufw disable
```

- Mostra le regole di ufw, con i numeri corrispondenti:

```bash
ufw status numbered
```

- Aperto al traffico in entrata sulla porta 5432, con un commento che identifica il servizio:

```bash
ufw allow 5432 comment "servizio"
```

- Aperto solo al traffico TCP da 192.168.0.4 a qualsiasi indirizzo su questo host, sulla porta 22:

```bash
ufw allow proto tcp from 192.168.0.4 to any port 22
```

- Blocchi traffico su porta 80 su questo host:

```bash
ufw deny 80
```

- Nega tutto il traffico UDP alla porta 22:

```bash
ufw deny proto udp from any to any port 22
```

- Elimina una regola particolare. Il numero della regola può essere trovato con "ufw status numbered":

```bash
ufw delete numero_della_regola
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

