---
author: ['bl-ue', 'Flex Zhong', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "konsole"
description: "konsole, Konsole: KDE 终端模拟器。"
categories: "linux"
---
> 更多信息：<https://konsole.kde.org>.

- 在特定目录中打开一个新的 Konsole：

```bash
konsole --workdir path/to/directory
```

- 运行特定命令，退出窗口后不要关闭窗口：

```bash
konsole --noclose -e 命令
```

- 打开新标签页：

```bash
konsole --new-tab
```

- 在后台打开 Konsole 并在按下 Ctrl+Shift+F12（默认）时显示在最前面：

```bash
konsole --background-mode
```

- 使用紧急备冗配置文件打开 Konsole：

```bash
konsole --fallback-profile
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | konsole, tldr: add Chinese translation & add --update example (#4469) | 2020-10-05T16:28:59 | [ece4c00efde1](https://github.com/tldr-pages/tldr/commit/ece4c00efde142048489c31951cfe7666010e7aa)

