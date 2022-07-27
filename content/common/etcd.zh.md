---
author: ['BillLucky', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "etcd, TLDR Pages"
description: "etcd, 分布式，可靠的键值存储，用于分布式系统中存储最关键的数据。"
categories: "common"
---
> 更多信息：<https://etcd.io>.

- 启动单节点 etcd 集群：

```bash
etcd
```

- 启动一个单节点 etcd 集群，在自定义 URL 上侦听客户端请求：

```bash
etcd --advertise-client-urls http://127.0.0.1:1234 --listen-client-urls http://127.0.0.1:1234
```

- 使用自定义名称启动单节点 etcd 集群：

```bash
etcd --name my_etcd_cluster
```

- 启动单节点 etcd 集群，同时可以在这里看到大量监控指标 http://localhost:2379/debug/pprof/：

```bash
etcd --enable-pprof --metrics extensive
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | etcd: add Chinese translation (#6032) | 2021-05-23T16:50:20 | [0731957862c4](https://github.com/tldr-pages/tldr/commit/0731957862c409b354470d51eca147ae8f48497b)

