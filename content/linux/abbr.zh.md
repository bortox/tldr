---
author: ['千玄子']
date: 1656677171
title: "abbr, TLDR Pages"
description: "abbr, 管理 fish shell 的缩写。"
categories: "linux"
---
> 用户定义的词在输入后会被较长的短语替换。

> 更多信息：<https://fishshell.com/docs/current/cmds/abbr.html>.

- 添加一个新缩写：

```bash
abbr --add 缩写名 命令 命令参数
```

- 重命名一个已有的缩写：

```bash
abbr --rename 旧缩写名 新缩写名
```

- 清除一个已有的缩写：

```bash
abbr --erase 缩写名
```

- 用 SSH 导入另一台主机上定义的缩写：

```bash
ssh 主机名 abbr --show | source
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | abbr: add Chinese translation (#8168) | 2022-07-01T14:06:11 | [b3c24bd62a86](https://github.com/tldr-pages/tldr/commit/b3c24bd62a86964bf527bd3e6bf65f735855d687)

