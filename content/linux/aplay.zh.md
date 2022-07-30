---
author: ['千玄子', 'bl-ue', 'marchersimon']
date: 1630394029
title: "aplay"
description: "aplay, ALSA 声卡驱动程序的命令行声音播放器。"
categories: "linux"
---
> 更多信息：<https://manned.org/aplay>.

- 播放一个文件（会自动根据文件格式确定采样率、位深等）：

```bash
aplay 文件路径
```

- 以 2500 Hz 播放指定文件的前 10 秒：

```bash
aplay --duration=10 --rate=2500 文件路径
```

- 以 22050 Hz，mono，8-bit，Mu-Law 和 `.au` 格式来播放指定原始文件：

```bash
aplay --channels=1 --file-type raw --rate=22050 --format=mu_law 文件路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

