---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker inspect, TLDR Pages"
description: "docker inspect, Mostra informazioni a basso livello di oggetti Docker."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/inspect/>.

- Mostra aiuto:

```bash
docker inspect
```

- Mostra informazioni su un container, immagine o volume usando un nome o un identificativo (ID):

```bash
docker inspect nome_container|nome_immagine|ID
```

- Mostra l'indirizzo IP di un container:

```bash
docker inspect --format='range .NetworkSettings.Networks.IPAddressend' nome_container
```

- Mostra il percorso dei file di log di un container:

```bash
docker inspect --format='.LogPath' nome_container
```

- Mostra il nome dell'immagine di un container:

```bash
docker inspect --format='.Config.Image' nome_container
```

- Mostra le informazioni di configurazione in formato JSON:

```bash
docker inspect --format='json .Config' nome_container
```

- Mostra il binding di tutte le porte:

```bash
docker inspect --format='range $p, $conf := .NetworkSettings.Ports $p -> (index $conf 0).HostPort end' nome_container
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

