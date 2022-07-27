---
author: ['千玄子']
date: 1631982664
title: "aura, TLDR Pages"
description: "aura, Aura 包管理器：一个安全且支持多语言的 Arch Linux 和 AUR 的包管理器。"
categories: "linux"
---
> 更多信息：<https://github.com/fosskers/aura>.

- 从官方仓库和 AUR 检索包：

```bash
aura --aursync --both --search 包名|正则
```

- 从 AUR 安装一个软件包：

```bash
aura --aursync 包名
```

- 以详细模式升级所有的 AUR 包并移除所有的编译依赖：

```bash
aura --aursync --diff --sysupgrade --delmakedeps --unsuppress
```

- 从官方仓库安装一个软件包：

```bash
aura --sync 包名
```

- 同步并更新官方仓库的所有软件包：

```bash
aura --sync --refresh --sysupgrade
```

- 使用包缓存降级一个软件包：

```bash
aura --downgrade 包名
```

- 移除一个软件包及其依赖：

```bash
aura --remove --recursive --unneeded 包名
```

- 移除孤儿包（作为依赖安装但现在不被任何包依赖）：

```bash
aura --orphans --abandon
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aura, brightnessctl: add Chinese translation (#6554) | 2021-09-18T18:31:04 | [f79d8e56e34f](https://github.com/tldr-pages/tldr/commit/f79d8e56e34f82ff4119e561902040fac6ed4c77)

