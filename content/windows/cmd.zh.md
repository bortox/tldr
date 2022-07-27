---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'Starccy', 'marchersimon']
date: 1648358715
title: "cmd, TLDR Pages"
description: "cmd, Windows 命令解释器。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- 开启一个新的命令行实例：

```bash
cmd
```

- 运行指定的命令然后退出：

```bash
cmd /c "命令"
```

- 执行一个指定的命令，之后进入一个交互式 shell：

```bash
cmd /k "命令"
```

- 不显示命令的输出结果：

```bash
cmd /q
```

- 启用或禁用命令扩展：

```bash
cmd /e:on|off
```

- 启用或禁用文件和目录名的自动补全：

```bash
cmd /f:on|off
```

- 启用或禁用环境变量扩展：

```bash
cmd /v:on|off
```

- 强制输出内容使用 Unicode 编码：

```bash
cmd /u
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | cmd: add Chinese translation | 2019-03-12T12:56:23 | [a7e95b4bba6c](https://github.com/tldr-pages/tldr/commit/a7e95b4bba6c8a05679348a8e6bc8452a36a594f)

