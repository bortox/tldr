---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'Kyle']
date: 1629747204
title: "asr"
description: "asr, 将磁盘映像还原（复制）到卷上。"
categories: "osx"
---
> 命令名称是 Apple Software Restore 的缩写。

> 更多信息：<https://www.unix.com/man-page/osx/8/asr/>.

- 将磁盘映像复制到目标卷：

```bash
sudo asr restore --source 映像名.dmg --target 卷路径
```

- 在复制之前擦除目标卷：

```bash
sudo asr restore --source 映像名.dmg --target 卷路径 --erase
```

- 恢复后跳过验证步骤：

```bash
sudo asr restore --source 映像名.dmg --target 卷路径 --noverify
```

- 不使用中间磁盘映像直接复制卷中的数据：

```bash
sudo asr restore --source 卷路径 --target 复制卷路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | asr: add Chinese translation | 2019-02-26T19:50:35 | [2604c7c6e621](https://github.com/tldr-pages/tldr/commit/2604c7c6e6212a62e1b3386f267b1a80d83bf1ca)

