---
author: ['Ein Verne', 'Lucas Gabriel Schneider', 'Andy Chen', 'bl-ue', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "bash"
description: "bash, Bourne-Again SHell."
categories: "common"
---
> 兼容`sh`的命令行解释器。

> 更多信息：<https://gnu.org/software/bash/>.

- 启动交互式 shell：

```bash
bash
```

- 执行命令：

```bash
bash -c "command"
```

- 执行脚本文件：

```bash
bash file.sh
```

- 执行脚本文件，并将所有执行过的命令输出到终端：

```bash
bash -x file.sh
```

- 执行脚本文件，并在第一个错误处终止：

```bash
bash -e file.sh
```

- 从输入（stdin）读取命令：

```bash
bash -s
```

- 将跟随的所有选项原样传递到要执行的脚本文件（可与`-s`选项共用来将选项传递到来自输入的命令 / 脚本）：

```bash
bash --
```

- 打印 bash 的版本信息（使用`echo $BASH_VERSION`来获得纯粹的版本字符串）：

```bash
bash --version
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Andy Chen](mailto:andy200511@126.com) | bash: add zh translation | 2019-08-17T06:28:02 | [d155a6dcf565](https://github.com/tldr-pages/tldr/commit/d155a6dcf5651927a54397bfe0e77466e1e87b4f)

