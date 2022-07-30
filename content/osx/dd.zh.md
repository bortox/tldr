---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'Kyle']
date: 1629747204
title: "dd"
description: "dd, 转换并复制文件。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/dd.html>.

- 从 isohybrid 文件（如 archlinux-xxx.iso）制作可用于引导系统启动的 USB 驱动器：

```bash
dd if=文件.iso of=/dev/usb 设备
```

- 将驱动器克隆到具有 4MB 块的另一个驱动器并忽略错误：

```bash
dd if=/dev/源设备 of=/dev/目标设备 bs=4m conv=noerror
```

- 使用内核随机驱动程序生成 100 个随机字节的文件：

```bash
dd if=/dev/urandom of=目标驱动器，接收随机数据文件名 bs=100 count=1
```

- 对磁盘的写入性能进行基准测试：

```bash
dd if=/dev/zero of=1GB 的文件名 bs=1024 count=1000000
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | dd: add Chinese translation | 2019-02-26T19:50:35 | [f014ec240596](https://github.com/tldr-pages/tldr/commit/f014ec240596aae26bf6cc62696f59aef7b734ad)

