---
author: ['千玄子', 'bl-ue', 'marchersimon']
date: 1630394029
title: "asterisk"
description: "asterisk, 电话和交换（手机）服务器。"
categories: "linux"
---
> 用于管理服务器自身和管理已经在运行的实例。

> 更多信息：<https://wiki.asterisk.org/wiki/display/AST/Home>.

- 重新连接一个正在运行的服务器，并打开 3 级的日志详细度：

```bash
asterisk -r -vvv
```

- 重新连接一个正在运行的服务器，执行一个命令，然后返回：

```bash
asterisk -r -x "命令"
```

- 显示 chan_SIP 客户端（手机）：

```bash
asterisk -r -x "sip show peers"
```

- 显示激活的通话和频道：

```bash
asterisk -r -x "core show channels"
```

- 显示语音邮箱：

```bash
asterisk -r -x "voicemail show users"
```

- 终止一个频道：

```bash
asterisk -r -x "hangup request 频道 ID"
```

- 重新载入 chan_SIP 设置：

```bash
asterisk -r -x "sip reload"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

