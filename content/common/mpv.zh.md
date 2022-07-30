---
author: ['bl-ue', 'Alan Chang', 'marchersimon']
date: 1630394029
title: "mpv"
description: "mpv, 一个基于 MPlayer 的音频/视频播放器。"
categories: "common"
---
> 更多信息：<https://mpv.io>.

- 播放一个音频或视频文件：

```bash
mpv 文件名
```

- 往后/往前 跳跃 5 秒：

```bash
LEFT <or> RIGHT
```

- 往后/往前 跳跃一分钟：

```bash
DOWN <or> UP
```

- 减少/增加 10% 播放速度：

```bash
[ <or> ]
```

- 以指定速度播放文件（0.01 到 100, 默认是 1）：

```bash
mpv --speed 速度 文件名
```

- 用 `mpv.conf` 中指定的一个用户配制播放文件：

```bash
mpv --profile 配制名称 文件名
```

- 播放摄像头或其他设备的输出：

```bash
mpv /dev/video0
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Alan Chang](mailto:tcode2k16@users.noreply.github.com) | node, mpv: add Chinese translation (#4579) | 2020-10-08T21:38:57 | [8381135cb729](https://github.com/tldr-pages/tldr/commit/8381135cb729d204ed10a482033c7fa89102fa0c)

