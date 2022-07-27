---
author: ['Anja Elzinger', '千玄子']
date: 1634201302
title: "beep, TLDR Pages"
description: "beep, 让电脑扬声器发出哔哔声的实用程序。"
categories: "linux"
---
> 更多信息：<https://github.com/spkr-beep/beep>.

- 播放哔哔声：

```bash
beep
```

- 重复播放哔哔声：

```bash
beep -r 重复次数
```

- 指定频率（Hz）和持续时间（毫秒）播放哔哔声：

```bash
beep -f 频率 -l 持续时间
```

- 将每个新的频率和持续时间作为单独的哔哔声播放：

```bash
beep -f 频率 -l 持续时间 -n -f 频率 -l 持续时间
```

- 播放 C 大调：

```bash
beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Anja Elzinger](mailto:35960947+entensee403@users.noreply.github.com) | beep: add German translation (#6939) | 2021-10-14T10:48:22 | [6c5fe7692586](https://github.com/tldr-pages/tldr/commit/6c5fe7692586c9913e3b490efffc5011764ccadc)
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

