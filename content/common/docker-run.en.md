---
author: ['Andrey Bienkowski', 'michaeldel', 'Alejandro Bezdjian', 'Muhammad Falak R Wani']
date: 1659013407
title: "docker run"
description: "docker run, Run a command in a new Docker container."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/run/>.

- Run command in a new container from a tagged image:

```bash
docker run image:tag command
```

- Run command in a new container in background and display its ID:

```bash
docker run --detach image command
```

- Run command in a one-off container in interactive mode and pseudo-TTY:

```bash
docker run --rm --interactive --tty image command
```

- Run command in a new container with passed environment variables:

```bash
docker run --env 'variable=value' --env variable image command
```

- Run command in a new container with bind mounted volumes:

```bash
docker run --volume /path/to/host_path:/path/to/container_path image command
```

- Run command in a new container with published ports:

```bash
docker run --publish host_port:container_port image command
```

- Run command in a new container overwriting the entrypoint of the image:

```bash
docker run --entrypoint command image
```

- Run command in a new container connecting it to a network:

```bash
docker run --network network image
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | docker-run: use long options for examples (#8262) | 2022-07-28T15:03:27 | [b7c8b55849e7](https://github.com/tldr-pages/tldr/commit/b7c8b55849e7ace9394c375e6533a920682c0a78)
[Andrey Bienkowski](mailto:hexagonrecursion@gmail.com) | docker: use absolute paths in `-v` example (#7762) Volume paths must be absolute instead of relative. | 2022-02-08T09:56:31 | [11e78ec50afa](https://github.com/tldr-pages/tldr/commit/11e78ec50afa2424221e862ef8c08fb10d4c60d4)
[Alejandro Bezdjian](mailto:alebezdjian@gmail.com) | docker-run: add --entrypoint and --network examples (#7208) | 2021-11-06T21:18:08 | [60bc47a5fb17](https://github.com/tldr-pages/tldr/commit/60bc47a5fb175ce41c83bfc89402695f9f5f54fa)
[michaeldel](mailto:michaeldel@protonmail.com) | docker-run: add page (#4054) | 2020-05-19T10:21:38 | [86f429422d9d](https://github.com/tldr-pages/tldr/commit/86f429422d9dd854cffba29e0bef8fde237e388e)

