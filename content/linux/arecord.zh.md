---
author: ['marchersimon']
date: 1633112881
title: "arecored, TLDR Pages"
description: "arecored, ALSA 声卡驱动的声音录制器。"
categories: "linux"
---
> 更多信息：<https://manned.org/arecord>.

- 以 "CD" 质量录制一段声音（录制结束以 Ctrl-C 停止）：

```bash
arecord -vv --format=cd 路径/文件名.wav
```

- 以 "CD" 质量录制 10 秒钟声音：

```bash
arecord -vv --format=cd --duration=10 路径/文件名.wav
```

- 录制一段声音并以 mp3 格式保存（录制结束以 Ctrl-C 停止）：

```bash
arecord -vv --format=cd --file-type raw | lame -r - 路径/文件名.mp3
```

- 列出所有的声卡和数字音频设备：

```bash
arecord --list-devices
```

- 允许交互式界面（例如使用空格键或回车键来播放或暂停）：

```bash
arecord --interactive
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arecord: fix name of Chinese page (#6289) | 2021-08-03T10:53:05 | [12ca1c7f957d](https://github.com/tldr-pages/tldr/commit/12ca1c7f957dd7e3facda25632ff6d0f07df8081)

