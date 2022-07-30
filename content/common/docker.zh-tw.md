---
author: ['lincc', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "docker"
description: "docker, 管理 Docker 容器和映像檔。"
categories: "common"
---
> 此命令也有關於其子命令的文件，例如：`docker run`.

> 更多資訊：<https://docs.docker.com/engine/reference/commandline/cli/>.

- 列出目前正在運行的 docker 容器：

```bash
docker ps
```

- 列出所有 docker 容器（包括停止的容器）：

```bash
docker ps -a
```

- 透過映像檔啟動容器，並為容器命名：

```bash
docker run --name 容器名稱 映像檔
```

- 啟動或停止現有容器：

```bash
docker start|stop 容器名稱
```

- 從 docker registry 中拉取映像檔：

```bash
docker pull 映像檔
```

- 從正在運行的容器內打開一個 shell：

```bash
docker exec -it 容器名稱 sh
```

- 刪除一個停止的容器：

```bash
docker rm 容器名稱
```

- 獲取並查看容器的日誌：

```bash
docker logs -f 容器名稱
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | docker: add Chinese translation (#6230) | 2021-07-15T17:32:11 | [38a68dd9d531](https://github.com/tldr-pages/tldr/commit/38a68dd9d5319cbb90ff789fdbc6371775bc36c6)

