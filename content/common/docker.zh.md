---
author: ['lincc', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "docker"
description: "docker, 管理 Docker 容器和镜像。"
categories: "common"
---
> 此命令也有关于其子命令的文件，例如：`docker run`.

> 更多信息：<https://docs.docker.com/engine/reference/commandline/cli/>.

- 列出目前正在运行的 docker 容器：

```bash
docker ps
```

- 列出所有 docker 容器（包括停止的容器）：

```bash
docker ps -a
```

- 透过镜像启动容器，并为容器命名：

```bash
docker run --name 容器名称 镜像
```

- 启动或停止现有容器：

```bash
docker start|stop 容器名称
```

- 从 docker registry 中拉取镜像：

```bash
docker pull 镜像
```

- 从正在运行的容器内打开一个 shell：

```bash
docker exec -it 容器名称 sh
```

- 删除一个停止的容器：

```bash
docker rm 容器名称
```

- 获取并查看容器的日志：

```bash
docker logs -f 容器名称
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | docker: add Chinese translation (#6230) | 2021-07-15T17:32:11 | [38a68dd9d531](https://github.com/tldr-pages/tldr/commit/38a68dd9d5319cbb90ff789fdbc6371775bc36c6)

