---
author: ['xBLACKICEx']
date: 1656071336
title: "ln"
description: "ln, 创建指向文件和目录的链接。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/ln>.

- 创建指向文件或目录的符号链接：

```bash
ln -s /路径/到/文件或目录 路径/到/符号链接
```

- 覆盖现有的符号链接以指向其他文件：

```bash
ln -sf /路径/到/新文件 路径/到/符号链接
```

- 创建文件的硬链接：

```bash
ln /路径/到/文件 路径/到/硬链接
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[xBLACKICEx](mailto:xBLACKICEx@outlook.com) | cp: add Chinese translation (#8133) | 2022-06-24T13:48:56 | [70b1ad7e23ad](https://github.com/tldr-pages/tldr/commit/70b1ad7e23ade8fb6b64230b54cc1a065091d820)

