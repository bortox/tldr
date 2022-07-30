---
author: ['Triad']
date: 1635550772
title: "iptables"
description: "iptables, Programma che permette di configurare tabelle, catene e regole fornite dal firewall del kernel Linux."
categories: "linux"
---
> Maggiori informazioni: <https://www.netfilter.org/projects/iptables/>.

- Visualizza catene, regole e contatori di pacchetti/byte per la tabella dei filtri:

```bash
sudo iptables -vnL
```

- Imposta regola ad una catena:

```bash
sudo iptables -P catena regola
```

- Appendi regola ad una catena di policy per IP:

```bash
sudo iptables -A catena -s ip -j regola
```

- Appendi regola ad una catena di policy per IP considerando protocollo e porta:

```bash
sudo iptables -A catena -s ip -p protocollo --dport porta -j regola
```

- Cancella regola da una catena:

```bash
sudo iptables -D catena numero_di_linea_della_regola
```

- Salva la configurazione di ip tables di una specifica tabella in un file:

```bash
sudo iptables-save -t nome tabella > percorso/al/file_iptables
```

- Ripristina la configurazione di iptables da un file:

```bash
sudo iptables-restore < percorso/al/file_iptables
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Triad](mailto:33317323+MrTriad@users.noreply.github.com) | iptables: add Italian translation (#7281) | 2021-10-30T01:39:32 | [ce423ade0086](https://github.com/tldr-pages/tldr/commit/ce423ade0086982cbf0e86c9ae304efcc09db5ee)

