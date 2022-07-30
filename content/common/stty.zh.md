---
author: ['Dario Vladović', 'bl-ue', 'Tomek Szczęsny', 'marchersimon']
date: 1630394029
title: "stty"
description: "stty, 设置终端设备接口的选项。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/stty>.

- 显示当前终端的所有设置：

```bash
stty -a
```

- 设置行数：

```bash
stty rows 行数
```

- 设置列数：

```bash
stty cols 列数
```

- 获取设备的实际传输速度：

```bash
stty -F 目标 / 文件夹 / 驱动设备文件 speed
```

- 将当前终端的所有模式重置为合理值：

```bash
stty sane
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Tomek Szczęsny](mailto:44300715+tomek-szczesny@users.noreply.github.com) | stty: fix typo (#6055) According to `stty --help`, the `-F` argument must be capital (lowercase is not recognized). Some Asian [...] | 2021-05-28T00:58:42 | [404065adae45](https://github.com/tldr-pages/tldr/commit/404065adae45d6460e0567046ba4ce2a2db85811)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | stty: add link (#5628) | 2021-03-30T16:01:53 | [bb744d7f2725](https://github.com/tldr-pages/tldr/commit/bb744d7f27251d9525afd9f72714779f6044cf75)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arch, bzip2, command, gunicorn, history, htop, shasum, stty, yes: move translation to correct directories (#5362) | 2021-03-07T21:50:02 | [9ffbe151a610](https://github.com/tldr-pages/tldr/commit/9ffbe151a610c34f28be6b04816bfe83e9145104)

