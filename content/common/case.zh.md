---
author: ['bl-ue', 'zhouquan', 'marchersimon']
date: 1630394029
title: "case"
description: "case, case ... esac 与其他语言中的 switch ... case 语句类似，是一种多分枝选择结构。"
categories: "common"
---
> 更多信息：<https://manned.org/case>.

- 通过字符串字面量判断执行分支：

```bash
case 入参变量 in 字符字面量1 执行语句块1 ;; 字符字面量2) 执行语句块2 ;; *) 默认执行语句块 ;; esac
```

- 搭配通配符进行匹配，判断执行分支：

```bash
case 入参变量 in 通配符或者字符字面量) 执行语句块1 ; ;; 通配符或者字符字面量) 执行语句块1; ;; *) echo "what?"; ;; esac
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | case: add link | 2021-04-18T16:33:27 | [4d87a4e1a562](https://github.com/tldr-pages/tldr/commit/4d87a4e1a562f8aa1581c21aa263994d3c5078fa)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

