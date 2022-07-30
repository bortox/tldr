---
author: ['Ein Verne', 'wizarot', 'Kyle', 'Mikey Garcia', 'bl-ue', 'Seth Falco']
date: 1648358715
title: "date"
description: "date, 设置或显示系统日期。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/date.html>.

- 使用默认区域设置的格式显示当前日期：

```bash
date +"%c"
```

- 以 UTC 和 ISO 8601 格式显示当前日期：

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- 将当前日期显示为 unix 时间戳（自 1970-01-01 00:00:00 以来的秒数）：

```bash
date +%s
```

- 使用默认格式显示特定日期（格式化指定 UNIX 时间戳）：

```bash
date -r 1473305798
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Revert "date: fix typo (#4069)" (#5997) | 2021-05-20T18:36:10 | [33b5fcd7bdc9](https://github.com/tldr-pages/tldr/commit/33b5fcd7bdc9e3e169e3a3c5c8b767dcb05b770e)
[Mikey Garcia](mailto:gikeymarcia@gmail.com) | date: fix typo (#4069) | 2020-05-27T05:46:20 | [e0151803205b](https://github.com/tldr-pages/tldr/commit/e0151803205bb7efa1e2222a979580dbcfc19589)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | date: add Chinese translation | 2019-02-26T19:50:35 | [de606c8e87a7](https://github.com/tldr-pages/tldr/commit/de606c8e87a7a339819ea4ef708b5a56d1f74013)

