---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1630394029
title: "arp, TLDR Pages"
description: "arp, 显示和操作系统的 ARP 缓存。"
categories: "common"
---
> 更多信息：<https://manned.org/arp>.

- 显示当前的 ARP 表：

```bash
arp -a
```

- 清除整个缓存：

```bash
sudo arp -a -d
```

- 删除特定条目：

```bash
arp -d 地址
```

- 创建指定条目：

```bash
arp -s 地址 MAC 地址
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | arp: add Chinese translation | 2019-04-17T21:44:55 | [1e1718e89496](https://github.com/tldr-pages/tldr/commit/1e1718e8949627551cd8be5d755bd7171f59dc46)
[Starccy](mailto:452276725@qq.com) | arp: add Chinese translation | 2019-04-17T21:44:55 | [7650cf7746bf](https://github.com/tldr-pages/tldr/commit/7650cf7746bffc63e201c17e5aa3761675ebd930)

