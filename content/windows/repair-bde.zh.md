---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "repair-bde"
description: "repair-bde, 尝试修复或解密损坏的 BitLocker 加密卷。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/repair-bde>.

- 尝试修复一个指定的卷：

```bash
repair-bde C:
```

- 尝试修复指定的卷并输出到另一个卷：

```bash
repair-bde C: D:
```

- 尝试使用提供的恢复密钥文件修复指定的卷：

```bash
repair-bde C: -RecoveryKey bek 文件的路径
```

- 尝试使用提供的数字恢复密码修复指定的卷：

```bash
repair-bde C: -RecoveryPassword 密码
```

- 尝试使用提供的密码修复指定的卷：

```bash
repair-bde C: -Password 密码
```

- 尝试使用提供的密钥包修复指定的卷：

```bash
repair-bde C: -KeyPackage 目录的路径
```

- 将日志输出到指定的文件：

```bash
repair-bde C: -LogFile 文件的路径
```

- 显示所有可用的选项：

```bash
repair-bde /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | repair-bde: add Chinese translation | 2019-03-12T12:56:23 | [249b3cdc127a](https://github.com/tldr-pages/tldr/commit/249b3cdc127ac367993d5ff55d40b179fd9af99e)

