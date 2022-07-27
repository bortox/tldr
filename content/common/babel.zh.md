---
author: ['zhouquan', 'meowmeowcat', 'marchersimon', 'bl-ue']
date: 1636827105
title: "babel, TLDR Pages"
description: "babel, 一款 JavaScript 的编译器，将下一代 ES 语法转换为兼容语法。"
categories: "common"
---
> 更多信息：<https://babeljs.io/>.

- 转编译指定文件到标准输出：

```bash
babel 路径/到/文件
```

- 转编译指定文件，输入为特定文件：

```bash
babel 路径/到/输入文件 --out-file 路径/到/输出文件
```

- 监听文件变动触发转编译：

```bash
babel 路径/到/输入文件 --watch
```

- 转编译整个目录下的 js 文件：

```bash
babel 路径/到/输入文件目录
```

- 跳过指定目录下指定文件的编译（多文件使用英文逗号“,”分隔）：

```bash
babel 路径/到/输入文件目录 --ignore 被忽略文件
```

- 转编译后，执行压缩：

```bash
babel 路径/到/输入文件 --minified
```

- 使用预设值：

```bash
babel 路径/到/输入文件 --presets 预设项
```

- 输出所有可用的选项：

```bash
babel --help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | babel: update Chinese translation (#7426) | 2021-11-13T19:11:45 | [07aca8e56442](https://github.com/tldr-pages/tldr/commit/07aca8e564423654cb9bd56dff31c33a7abaf046)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

