---
author: ['千玄子', 'Maksim Verkhoturov']
date: 1657894274
title: "brightnessctl, TLDR Pages"
description: "brightnessctl, GUN/Linux 操作系统上用来读取和控制设备亮度的实用工具。"
categories: "linux"
---
> 更多信息：<https://github.com/Hummer12007/brightnessctl>.

- 列出亮度可变的设备：

```bash
brightnessctl --list
```

- 打印显示器当前亮度：

```bash
brightnessctl get
```

- 将显示器背光的亮度设置为指定的百分比：

```bash
brightnessctl set 50%
```

- 按指定的增量增加亮度：

```bash
brightnessctl set +10%
```

- 将亮度降低指定的递减量：

```bash
brightnessctl set 10%-
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Maksim Verkhoturov](mailto:sd32@protonmail.com) | brightnessctl: fix typo in decrease example (#8213) | 2022-07-15T16:11:14 | [50f543866e0c](https://github.com/tldr-pages/tldr/commit/50f543866e0cbe34d70b19cc1eca4cd53a8f8120)
[千玄子](mailto:ownbyzjuyk@gmail.com) | aura, brightnessctl: add Chinese translation (#6554) | 2021-09-18T18:31:04 | [f79d8e56e34f](https://github.com/tldr-pages/tldr/commit/f79d8e56e34f82ff4119e561902040fac6ed4c77)

