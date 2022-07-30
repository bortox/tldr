---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "choco new"
description: "choco new, 使用 Chocolatey 生成新的包规范文件。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-new>.

- 创建一个新的包框架：

```bash
choco new 包名
```

- 创建一个新的指定版本的包：

```bash
choco new 包名 --version 版本号
```

- 创建一个新的包并指定维护者的名字：

```bash
choco new 包名 --maintainer 维护者名字
```

- 在指定目录下创建新的包：

```bash
choco new 包名 --output-directory 指定的目录路径
```

- 创建一个新的包并指定其 32 位版和 64 位版的安装 URL：

```bash
choco new package_name url="url" url64="url"
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
[Starccy](mailto:452276725@qq.com) | choco-new: add Chinese translation | 2019-03-12T12:56:23 | [5e6f15e4e0fe](https://github.com/tldr-pages/tldr/commit/5e6f15e4e0fef072ce65e5b9ffc5704b4ecb0d09)

