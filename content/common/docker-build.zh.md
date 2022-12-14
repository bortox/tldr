---
author: ['BillLucky']
date: 1629041216
title: "docker build"
description: "docker build, 从 Dockerfile 打包镜像。"
categories: "common"
---
> 更多信息：<https://docs.docker.com/engine/reference/commandline/build/>.

- 使用当前目录下的 Dockerfile 打包一个 docker 镜像：

```bash
docker build .
```

- 从指定 URL 的 Dockerfile 打包 docker 镜像：

```bash
docker build github.com/creack/docker-firefox
```

- 打包一个 docker 镜像并指定镜像的标签：

```bash
docker build --tag name:tag .
```

- 打包一个没有上下文的 docker 镜像：

```bash
docker build --tag name:tag - < Dockerfile
```

- 打包镜像时不使用缓存：

```bash
docker build --no-cache --tag name:tag .
```

- 使用指定的 Dockerfile 打包一个 docker 镜像：

```bash
docker build --file Dockerfile .
```

- 传入自定义变量用于打包：

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[BillLucky](mailto:bill.libiao@gmail.com) | docker-build: add Chinese translation (#6314) | 2021-08-15T17:26:56 | [6bf3f8134a5c](https://github.com/tldr-pages/tldr/commit/6bf3f8134a5ce1280bb9363aa25433fdf8e8cc8d)

