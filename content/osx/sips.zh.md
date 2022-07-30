---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'marchersimon', 'wizarot']
date: 1659075216
title: "sips, TLDR Pages"
description: "sips, 苹果的处理文件脚本系统。"
categories: "osx"
---
> 光栅 / 查询图像 和 颜色同步 ICC 配置文件。

> 更多信息：<https://ss64.com/osx/sips.html>.

- S 指定一个输出目录，这样原始文件就不会被修改：

```bash
sips --out 目标 / 文件夹 / 输出文件夹
```

- 以指定的大小对图像重新采样，图像纵横比可能会更改：

```bash
sips -z 1920 300 图片文件。扩展名
```

- 对图像重新取样，使高度和宽度不大于指定的大小（注意大写 Z）：

```bash
sips -Z 1920 300 图片文件。扩展名
```

- 对目录中的所有图像重新取样，以适应 960px 的宽度（保持纵横比）：

```bash
sips --resampleWidth 960 目标 / 文件夹 / 所有图片文件
```

- 将图像从 CMYK 转换为 RGB：

```bash
sips --matchTo '/System/Library/ColorSync/Profiles/Generic RGB Profile.icc' 目标 / 文件夹 / 图片。扩展 目标 / 文件夹 / 输出文件夹
```

- 从图像中删除 ColorSync ICC 配置：

```bash
sips -d profile --deleteColorManagementProperties 目标 / 文件夹 / 图片。扩展
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | sips: add Chinese translation | 2019-03-15T12:47:29 | [3228dc020659](https://github.com/tldr-pages/tldr/commit/3228dc020659367afa042502c265b1117f2c0635)

