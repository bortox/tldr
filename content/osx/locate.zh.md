---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'Gear J']
date: 1633928905
title: "locate"
description: "locate, 快速查找文件名。"
categories: "osx"
---
> 更多信息：<https://manned.org/locate>.

- 在数据库中查找关键字。注意：数据库定期重新更新（通常每周或每天）：

```bash
locate 关键字
```

- 按文件名查找文件（不包含填充字符的模式被解释为 `*关键字*`）：

```bash
locate */文件名
```

- 重新建立文件数据索引数据库。如果要查找最近添加的文件，则需要执行此操作：

```bash
sudo /usr/libexec/locate.updatedb
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Gear J](mailto:12108619+gearj@users.noreply.github.com) | launchctl, lldb, locate, look: add more information link (#6893) | 2021-10-11T07:08:25 | [fcc03f1e6ff9](https://github.com/tldr-pages/tldr/commit/fcc03f1e6ff9776ca4433447e9859a3c1a42e539)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | locate: add Chinses translation | 2019-03-05T09:15:04 | [503fa433c2c8](https://github.com/tldr-pages/tldr/commit/503fa433c2c8945a07ad85733177035bd175b066)

