---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "alias"
description: "alias, 创建别名 -- 用给定的字符串指代特定的命令。"
categories: "common"
---
> 别名只会在当前的 shell 会话中生效，除非它们在 shell 的配置文件中被定义，例如`~/.bashrc`.

> 更多信息：<https://tldp.org/LDP/abs/html/aliases.html>.

- 创建一个通用的别名：

```bash
alias 别名="命令"
```

- 通过给定的别名查看它所指代的命令：

```bash
alias 别名
```

- 移除一个别名：

```bash
unalias 别名
```

- 列出所有的别名：

```bash
alias -p
```

- 将 rm 转换为交互式命令：

```bash
alias rm="rm -i"
```

- 创建别名 `la` 来指代 `ls -a`：

```bash
alias la="ls -a"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | alias: add Chinese translation | 2019-04-17T21:44:55 | [6a5f361f0182](https://github.com/tldr-pages/tldr/commit/6a5f361f0182ccf2b5ea83bd46f5d40e3281258c)
[Starccy](mailto:452276725@qq.com) | alias: add Chinese translation | 2019-04-17T21:44:55 | [9ddfb03f0bd2](https://github.com/tldr-pages/tldr/commit/9ddfb03f0bd284dba1fb85facbb66e151972fa3b)

