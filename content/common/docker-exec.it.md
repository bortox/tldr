---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker exec"
description: "docker exec, Esegui un comando su un Docker container in esecuzione."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/exec/>.

- Avvia una shell interattiva all'interno di un container in esecuzione:

```bash
docker exec --interactive --tty nome_container /bin/bash
```

- Esegui un commando in background ("detached") su un container in esecuzione:

```bash
docker exec --detach nome_container comando
```

- Seleziona la directory di lavoro in cui eseguire un dato comando:

```bash
docker exec --interactive -tty --workdir percorso/alla/directory nome_container comando
```

- Esegui un comando in background su un container esistente, mantenendo aperto stdin:

```bash
docker exec --interactive --detach nome_container comando
```

- Imposta una variabile d'ambiente in una sessione bash in esecuzione:

```bash
docker exec --interactive --tty --env nome_variabile=valore nome_container /bin/bash
```

- Specifica l'utente da usare per eseguire un comando:

```bash
docker exec --user utente nome_container comando
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

