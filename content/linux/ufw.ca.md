---
author: ['Seifer23']
date: 1644117941
title: "ufw"
description: "ufw, Tallafocs sense complicacions (_Uncomplicated Firewall_)."
categories: "linux"
---
> Interfície d'usuari de iptables per facilitar la configuració d'un firewall.

> Més informació: <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- Activa ufw:

```bash
ufw enable
```

- Desactiva ufw:

```bash
ufw disable
```

- Mostra les regles del ufw, en conjunt amb els seus números:

```bash
ufw status numbered
```

- Permet el tràfic entrant en el port 5432 en aquest host amb un comentari que indentifiqui el servei:

```bash
ufw allow 5432 comment "servei"
```

- Permet només el tràfic TCP desde 192.168.0.4 a qualsevol direcció d'aquest host, en el port 22:

```bash
ufw allow proto tcp from 192.168.0.4 to any port 22
```

- Denega el tràfic en el port 80 en aquest host:

```bash
ufw deny 80
```

- Denega tot el tràfic al port 22:

```bash
ufw deny proto udp from any to any port 22
```

- Elimina una regla concreta. El número de la regla es pot obtenir del comanadament `ufw status numbered`:

```bash
ufw delete número_de_regla
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

