---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'Starccy', 'marchersimon']
date: 1648358715
title: "apg, TLDR Pages"
description: "apg, 生成任意复杂度的随机密码。"
categories: "common"
---
> 更多信息：<https://manned.org/apg>.

- 生成随机密码（默认密码长度为 8 位）：

```bash
apg
```

- 生成密码，包含至少 1 个符号 (S), 1 个数字 (N), 1 个大写字母 (C), 1 个小写字母 (L)：

```bash
apg -M SNCL
```

- 生成 16 个字符的密码：

```bash
apg -m 16
```

- 生成最大长度为 16 位的密码：

```bash
apg -x 16
```

- 生成未出现在字典中的密码（必须提供字典文件）：

```bash
apg -r 字典文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-18T16:33:27 | [9eb612378634](https://github.com/tldr-pages/tldr/commit/9eb612378634ff548a7da6c44f106f5e4625a161)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: edit link | 2021-04-18T16:33:27 | [ec6a3682f0fe](https://github.com/tldr-pages/tldr/commit/ec6a3682f0feaea05c28b65ddac54d395b32a284)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: add link | 2021-04-18T16:33:27 | [d5cbcd6fbca3](https://github.com/tldr-pages/tldr/commit/d5cbcd6fbca3201f690a82f177faf6679349e803)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | apg: add Chinese translation | 2019-04-17T21:44:55 | [7c49ba9d724e](https://github.com/tldr-pages/tldr/commit/7c49ba9d724e1cabfcc5dbf7c53a00defa41adc0)
[Starccy](mailto:452276725@qq.com) | apg: add Chinese translation | 2019-04-17T21:44:55 | [bf0973db69a9](https://github.com/tldr-pages/tldr/commit/bf0973db69a93393bd0e211d2eb9b9fb9d9c966f)

