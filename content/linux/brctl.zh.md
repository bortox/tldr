---
author: ['千玄子', 'Seth Falco']
date: 1648358715
title: "brctl"
description: "brctl, 以太网桥管理。"
categories: "linux"
---
> 更多信息：<https://manned.org/brctl>.

- 显示有关当前现有以太网网桥信息的列表：

```bash
sudo brctl show
```

- 创建新的以太网桥接接口：

```bash
sudo brctl add 网桥名
```

- 删除一个已存在的以太网桥接接口：

```bash
sudo brctl del 网桥名
```

- 向现有网桥添加接口：

```bash
sudo brctl addif 网桥名 接口名
```

- 从现有网桥中删除接口：

```bash
sudo brctl delif 网桥名 接口名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

