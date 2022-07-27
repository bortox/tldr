---
author: ['Flex Zhong', 'Dario Vladović', 'marchersimon']
date: 1630394029
title: "uname, TLDR Pages"
description: "uname, 输出关于当前机器和运行在该机器上的操作系统的详细信息。"
categories: "common"
---
> 注意：如需了解操作系统的其他信息，请尝试使用 `lsb_release` 命令。

> 更多信息：<https://www.gnu.org/software/coreutils/uname>.

- 打印硬件相关信息：机器和处理器：

```bash
uname -mp
```

- 打印软件相关信息：操作系统、发行号和版本：

```bash
uname -srv
```

- 打印系统的名称（主机名）：

```bash
uname -n
```

- 打印所有可用的系统信息（硬件、软件、名称）：

```bash
uname -a
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | uname: add more information link (#5633) | 2021-03-30T16:01:18 | [4f4592712cd8](https://github.com/tldr-pages/tldr/commit/4f4592712cd8655a7994d9d8d230c468b7bc8a38)
[Flex Zhong](mailto:chungzh07@gmail.com) | clear, uname: add Chinese translation (#4160) | 2020-07-08T14:30:42 | [87abf4a19752](https://github.com/tldr-pages/tldr/commit/87abf4a1975275339c226a34b3f857af2d9e0e57)

