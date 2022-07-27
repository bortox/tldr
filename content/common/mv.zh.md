---
author: ['Minghao Liu']
date: 1658068578
title: "mv, TLDR Pages"
description: "mv, 移动或重命名文件或目录。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/mv>.

- 移动文件到任意位置：

```bash
mv 来源 目标
```

- 移动文件到其他目录，并保持文件名不变：

```bash
mv 来源1 来源2 来源3 目标目录
```

- 覆盖现有文件前无需确认：

```bash
mv -f 来源 目标
```

- 无论是否有文件权限，覆盖现有文件前均需要确认：

```bash
mv -i 来源 目标
```

- 不要覆盖现有的目标文件：

```bash
mv -n 来源 目标
```

- 详细模式，移动后打印文件名：

```bash
mv -v 来源 目标
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | mv, whoami, whois: add Chinese translation (#8219) | 2022-07-17T16:36:18 | [2d1c118ce187](https://github.com/tldr-pages/tldr/commit/2d1c118ce187ab76d24ebcb08d8a0b31d7b213c6)

