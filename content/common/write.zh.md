---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'KsRyY', 'marchersimon']
date: 1659075216
title: "write, TLDR Pages"
description: "write, 向某个终端上的特定用户的屏幕写入信息（Ctrl-C 来停止写入）。"
categories: "common"
---
> 使用 `who` 命令来获取所有活动用户的终端 id. 参见 `mesg`.

> 更多信息：<https://manned.org/write>.

- 向指定的终端 ID 上的指定用户写入信息：

```bash
write username terminal_id
```

- 向终端 "/dev/tty/5" 上的用户 "testuser" 发送信息：

```bash
write testuser tty/5
```

- 向伪终端 "/dev/pts/5" 上的用户 "johndoe" 发送信息：

```bash
write johndoe pts/5
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[KsRyY](mailto:andy200511@126.com) | write: add Chinese translation | 2019-08-26T02:09:41 | [63039eb5e20a](https://github.com/tldr-pages/tldr/commit/63039eb5e20a2d9871672da490decabdfc7db1a4)

