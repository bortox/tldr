---
author: ['zhouquan', 'bl-ue', 'marchersimon', 'Fanyjie']
date: 1641986794
title: "bat, TLDR Pages"
description: "bat, 可以打印并且合并文件的命令。"
categories: "common"
---
> `cat` 的复制品，外加语法高亮和 Git 集成。

> 更多信息：<https://github.com/sharkdp/bat>.

- 文件内容打印：

```bash
bat 文件
```

- 多文件合并到目标文件：

```bash
bat 文件1 文件2 > 目标文件
```

- 在指定文件后追加多个文件合并的内容：

```bash
bat 文件1 文件2 >> 目标文件
```

- 打印时，显示行号：

```bash
bat -n 文件
```

- 高亮一个 `json` 文件：

```bash
bat --language json 文件.json
```

- 受支持的语言清单：

```bash
bat --list-languages
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Fanyjie](mailto:allandowney@126.com) | bat: fix typo in Chinese translation (#7640) | 2022-01-12T12:26:34 | [303e2ef2c615](https://github.com/tldr-pages/tldr/commit/303e2ef2c61572807d70543dee386d70e33b64e3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

