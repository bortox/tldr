---
author: ['Flex Zhong', 'bl-ue', 'marchersimon']
date: 1630394029
title: "clear, TLDR Pages"
description: "clear, 清空终端的屏幕。"
categories: "common"
---
> 更多信息：<https://manned.org/clear>.

- 清空屏幕（相当于在 Bash shell 中按 Control-L 键）：

```bash
clear
```

- 清空屏幕但保留终端的回滚缓冲区：

```bash
clear -x
```

- 指明要清空的终端类型（默认为环境变量 `TERM` 的值）：

```bash
clear -T type_of_terminal
```

- 显示 `clear` 使用的 `ncurses` 版本：

```bash
clear -V
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | clear: add link | 2021-04-18T16:33:27 | [907b82779088](https://github.com/tldr-pages/tldr/commit/907b827790882ee9086eb4d20cf8e3059343048a)
[Flex Zhong](mailto:chungzh07@gmail.com) | clear, uname: add Chinese translation (#4160) | 2020-07-08T14:30:42 | [87abf4a19752](https://github.com/tldr-pages/tldr/commit/87abf4a1975275339c226a34b3f857af2d9e0e57)

