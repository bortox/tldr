---
author: ['Ali Malek', 'Elijah Shackelford', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "docker exec, TLDR Pages"
description: "docker exec, Execute a command on an already running Docker container."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/exec/>.

- Enter an interactive shell session on an already-running container:

```bash
docker exec --interactive --tty container_name /bin/bash
```

- Run a command in the background (detached) on a running container:

```bash
docker exec --detach container_name command
```

- Select the working directory for a given command to execute into:

```bash
docker exec --interactive -tty --workdir path/to/directory container_name command
```

- Run a command in background on existing container but keep stdin open:

```bash
docker exec --interactive --detach container_name command
```

- Set an environment variable in a running Bash session:

```bash
docker exec --interactive --tty --env variable_name=value container_name /bin/bash
```

- Run a command as a specific user:

```bash
docker exec --user user container_name command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-exec: add new example (#4818) * docker-exec: add new example * docker-exec: fix options format | 2020-10-28T19:35:36 | [0f502c4f5417](https://github.com/tldr-pages/tldr/commit/0f502c4f5417635a1fa85c357a9442751ed55f83)
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | docker-exec: add page (#4518) | 2020-10-07T13:45:08 | [3c33a6b9876f](https://github.com/tldr-pages/tldr/commit/3c33a6b9876f85fe4fbf409413e01c8d5970a1b1)

