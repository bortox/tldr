---
author: ['bl-ue', 'Flex Zhong', 'marchersimon']
date: 1630394029
title: "dmesg"
description: "dmesg, 将内核消息写入标准输出。"
categories: "sunos"
---
> 更多信息：<https://www.unix.com/man-page/sunos/1m/dmesg>.

- 显示内核消息：

```bash
dmesg
```

- 显示此系统上可用的物理内存：

```bash
dmesg | grep -i memory
```

- 一次显示一页内核消息：

```bash
dmesg | less
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Flex Zhong](mailto:chungzh07@gmail.com) | dmesg, sv: add Chinese translation (#4389) * Create dmesg.md * Create sv.md | 2020-10-01T20:27:39 | [dfc79a1c6de3](https://github.com/tldr-pages/tldr/commit/dfc79a1c6de3eb283969a4b1927184dc8256db4c)

