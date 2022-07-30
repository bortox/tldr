---
author: ['Sebastian Göls', 'marchersimon']
date: 1631521281
title: "docker"
description: "docker, Verwalte Docker Container und Images."
categories: "common"
---
> Manche Unterbefehle wie `docker run` sind separat dokumentiert.

> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Liste zur Zeit laufende Container auf:

```bash
docker ps
```

- Liste laufende und gestoppte Container auf:

```bash
docker ps -a
```

- Erzeuge einen Container aus einem Image und benenne ihn:

```bash
docker run --name container_name pfad/zu/image
```

- Stoppe oder starte einen existierenden Container:

```bash
docker start|stop container_name
```

- Lade ein Image herunter:

```bash
docker pull pfad/zu/image
```

- Öffne eine Konsole innerhalb eines bereits laufenden Containers:

```bash
docker exec -it container_name sh
```

- Lösche einen gestoppten Container:

```bash
docker rm container_name
```

- Zeige die Logs eines Containers an und aktualisiere sie automatisch:

```bash
docker logs -f container_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Sebastian Göls](mailto:6608231+Abrynos@users.noreply.github.com) | docker/de: add translation (#4691) | 2020-10-15T00:22:02 | [7161d65a40d6](https://github.com/tldr-pages/tldr/commit/7161d65a40d6a91621b469cbb6039f943e7ca6f2)

