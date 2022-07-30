---
author: ['Axel Navarro', 'git-em']
date: 1646145629
title: "rubocop"
description: "rubocop, 格式化 Ruby 文件。"
categories: "common"
---
> 更多信息：<https://docs.rubocop.org/rubocop/usage/basic_usage.html>.

- 检查当前目录中的所有文件（包括子目录）：

```bash
rubocop
```

- 检查一个或多个指定文件或目录：

```bash
rubocop 目录 / 文件名 目录 /
```

- 将输出写入指定文件：

```bash
rubocop --out 目录 / 文件名
```

- 查看规则列表（格式化规则）：

```bash
rubocop --show-cops
```

- 排除格式规则：

```bash
rubocop --except 规则 1 规则 2
```

- 只运行指定的规则：

```bash
rubocop --only 规则 1 规则 2
```

- 自动更正文件（实验）：

```bash
rubocop --auto-correct
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | rubocop: add link in Chinese translation (#7835) | 2022-03-01T15:40:29 | [f3cb84bc88a2](https://github.com/tldr-pages/tldr/commit/f3cb84bc88a27870dc05fd599e6625e30d749dfc)
[git-em](mailto:56173216+git-em@users.noreply.github.com) | brightness, n, open, pbcopy, pbpaste, rename, route, rubocop, softwareupdate, timed, where, while, xed, xip: add link (#7831) | 2022-03-01T14:21:17 | [2ce63b334ebd](https://github.com/tldr-pages/tldr/commit/2ce63b334ebd26bb9e46be904fcc19884974e397)

