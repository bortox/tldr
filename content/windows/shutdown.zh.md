---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "shutdown, TLDR Pages"
description: "shutdown, 用于关闭，重新启动或注销计算机的工具。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/shutdown>.

- 关闭当前的计算机：

```bash
shutdown /s
```

- 重启当前的计算机：

```bash
shutdown /r
```

- 休眠当前的计算机：

```bash
shutdown /h
```

- 注销当前的计算机：

```bash
shutdown /l
```

- 指定在关闭之前等待的时间（以秒为单位）：

```bash
shutdown /s /t 秒
```

- 指定一个关机的理由：

```bash
shutdown /s /c "理由"
```

- 在超时之前取消关机指令：

```bash
shutdown /a
```

- 关闭远程的计算机：

```bash
shutdown /m \\ 主机名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | shutdown: add Chinese translation | 2019-03-12T12:56:23 | [cd654d109721](https://github.com/tldr-pages/tldr/commit/cd654d10972104df2878da88f3e5daafd1246d6f)

