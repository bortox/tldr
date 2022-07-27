---
author: ['jinsihou19', 'lincc']
date: 1643487459
title: "zip, TLDR Pages"
description: "zip, 将文件打包并压缩（存档）为 zip 文件。"
categories: "common"
---
> 更多信息：<https://manned.org/zip>.

- 递归地打包和压缩文件和目录：

```bash
zip -r 压缩文件.zip 路径/到/文件 路径/到/目录1 路径/到/目录2
```

- 添加到压缩档案中并排除不需要的文件：

```bash
zip -r 压缩文件.zip 路径/到/目录 -x 路径/到/不需要的文件
```

- 使用最高压缩级别 9 压缩目录和内容：

```bash
zip -r -9 压缩文件.zip 路径/到/目录
```

- 创建一个加密压缩档案（将会提示输入密码）：

```bash
zip -e -r 压缩文件.zip 路径/到/目录
```

- 将文件添加到现有的 zip 文件：

```bash
zip 压缩文件.zip 路径/到/文件
```

- 从现有 zip 文件中删除文件：

```bash
zip -d 压缩文件.zip "foo/*.tmp"
```

- 将指定目录及其内容打包并拆分为多个 zip 文件（例如：若干个 3 GB 的 zip 包）：

```bash
zip -r -s 3g 压缩文件.zip 路径/到/目录
```

- 列出指定压缩档案中的文件（不提取文件）：

```bash
zip -sf 压缩文件.zip
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[jinsihou19](mailto:540097546@qq.com) | zip: add Chinese translation (#7277) | 2021-11-02T13:05:23 | [f3008053911a](https://github.com/tldr-pages/tldr/commit/f3008053911ad7fa5d44483695ab5d4117864ec2)

