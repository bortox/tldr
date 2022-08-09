---
author: ['Minghao Liu', 'Julien Tremblay McLellan - Library & Information Science', 'bl-ue', 'Mehrad Mahmoudian', 'Seth Falco', 'marchersimon']
date: 1659927118
title: "flameshot"
description: "flameshot, 带有 GUI 界面的 Screenshot 工具。"
categories: "linux"
---
> 支持基本的图像编辑，例如文本，形状，颜色和 imgur。

> 更多信息：<https://flameshot.org>.

- 全屏截图：

```bash
flameshot full
```

- 交互式截图：

```bash
flameshot gui
```

- 截图并保存到特定的路径：

```bash
flameshot gui --path 路径/到/目录
```

- 简单模式下交互式截图：

```bash
flameshot launcher
```

- 指定屏幕截图：

```bash
flameshot screen --number 2
```

- 截图并打印到标准输出：

```bash
flameshot gui --raw
```

- 截图并复制到剪切板：

```bash
flameshot gui --clipboard
```

- 延迟指定毫秒时间截图：

```bash
flameshot full --delay 5000
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | flameshot: fix Chinese translation (#8312) | 2022-08-08T04:51:58 | [8c9559dca879](https://github.com/tldr-pages/tldr/commit/8c9559dca8793883dbd066dbd211b71b20c0fc7a)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Mehrad Mahmoudian](mailto:m.mahmoudian@gmail.com) | flameshot: add examples and fix more info link (#6377) | 2021-08-17T14:43:01 | [381b52163f28](https://github.com/tldr-pages/tldr/commit/381b52163f284ef2fcabe68d607ffd6ae88f4df6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Julien Tremblay McLellan - Library & Information Science](mailto:jtremc@gmail.com) | flameshot: add Chinese translation (#4361) | 2020-10-01T22:07:47 | [6a9edff74523](https://github.com/tldr-pages/tldr/commit/6a9edff74523aa95bc35a031430351ad33e71663)

