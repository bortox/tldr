---
author: ['bl-ue', 'marchersimon', 'Ein Verne', 'wizarot']
date: 1659075216
title: "shuf, TLDR Pages"
description: "shuf, 生成随机排列。"
categories: "osx"
---
> 更多信息：<https://www.unix.com/man-page/linux/1/shuf/>.

- 随机化文件中的行顺序并输出结果：

```bash
shuf 文件名
```

- 只输出结果的前 5 条：

```bash
shuf -n 5 文件名
```

- 将结果输出写入另一个文件：

```bash
shuf 文件名 -o 输出_文件名
```

- 生成范围（1-10）内的随机数：

```bash
shuf -i 1-10
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | shuf: add Chinese translation | 2019-03-15T12:47:29 | [c8388fefb129](https://github.com/tldr-pages/tldr/commit/c8388fefb12949277e2cbde8184f971683b5e20b)

