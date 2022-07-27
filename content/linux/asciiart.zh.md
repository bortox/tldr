---
author: ['marchersimon', 'Flex Zhong', 'bl-ue', 'lincc']
date: 1645362230
title: "asciiart, TLDR Pages"
description: "asciiart, 将图像转换为 ASCII."
categories: "linux"
---
> 更多信息：<https://github.com/nodanaonlyzuul/asciiart>.

- 从文件中读取图像并以 ASCII 打印：

```bash
asciiart 路径/到/图片.jpg
```

- 从 URL 中读取图像并以 ASCII 打印：

```bash
asciiart www.example.com/image.jpg
```

- 选择输出宽度（默认为 100）：

```bash
asciiart -width 50 路径/到/图片.jpg
```

- 对 ASCII 输出进行着色：

```bash
asciiart --color 路径/到/图片.jpg
```

- 选择输出格式（默认格式为文本）：

```bash
asciiart --format text|html 路径/到/图片.jpg
```

- 反转字符映射：

```bash
asciiart --invert-chars 路径/到/图片.jpg
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | asciiart: update Chinese translation (#7792) | 2022-02-20T14:03:50 | [6b3ee7446773](https://github.com/tldr-pages/tldr/commit/6b3ee744677380017aee406cf65b90592d39a1d3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | Create asciiart.md (#4979) | 2020-11-26T15:19:00 | [2f748d49464c](https://github.com/tldr-pages/tldr/commit/2f748d49464c82faa0bf625748d1bfca1caa10a1)

