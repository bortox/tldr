---
author: ['千玄子', 'marchersimon']
date: 1633112881
title: "apt-add-repository"
description: "apt-add-repository, 管理 apt 仓库。"
categories: "linux"
---
> 更多信息：<https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- 添加一个 apt 仓库：

```bash
apt-add-repository repository_spec
```

- 移除一个 apt 仓库：

```bash
apt-add-repository --remove repository_spec
```

- 添加一个 apt 仓库之后更新包缓存：

```bash
apt-add-repository --update repository_spec
```

- 开启源码包：

```bash
apt-add-repository --enable-source repository_spec
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

