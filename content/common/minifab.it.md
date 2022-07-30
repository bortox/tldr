---
author: ['bl-ue', 'Mattia Righetti']
date: 1610731489
title: "minifab"
description: "minifab, Strumento per semplificare il settaggio e il deployment di una blockchain Hyperledger Fabric."
categories: "common"
---
> Maggiori informazioni: <https://github.com/hyperledger-labs/minifabric>.

- Crea la blockchain Hyperledger Fabric:

```bash
minifab up -i versione_minifab
```

- Rimuovi la blockchain Hyperledger Fabric:

```bash
minifab down
```

- Installa smart contract su un canale:

```bash
minifab install -n nome_smart_contract
```

- Installa smart contract su un canale specificando la versione:

```bash
minifab install -n nome_smart_contract -v versione_smart_contract
```

- Inizializza smart contract dopo installazione/aggiornamento dello stesso:

```bash
minifab approve,commit,initialize,discover
```

- Interroga smart contract con argomenti:

```bash
minifab invoke -n nome_smart_contract -p '"nome_metodo", "arg0", "arg1", ...'
```

- Interroga la blockchain:

```bash
minifab blockquery numero_blocco
```

- Esegui direttamente l'applicazione:

```bash
minifab apprun -l linguaggio_di_programmazione
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Mattia Righetti](mailto:matt95.righetti@gmail.com) | minifab: add page (#5030) * minifab: add page * minifab: italian translation | 2021-01-01T23:29:19 | [f8f15709368d](https://github.com/tldr-pages/tldr/commit/f8f15709368d9b43325eb517c8256f71f65cc1e5)

