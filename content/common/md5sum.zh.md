---
author: ['Dario Vladović', 'Flex Zhong', 'Axel Navarro', 'bl-ue', 'marchersimon']
date: 1630697779
title: "md5sum"
description: "md5sum, 计算 MD5 加密校验和。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/md5sum>.

- 计算文件的 MD5 校验和：

```bash
md5sum path/to/file
```

- 计算多个文件的 MD5 校验和：

```bash
md5sum path/to/file1 path/to/file2
```

- 读取 MD5SUM 的文件并验证所有文件是否具有匹配的校验和：

```bash
md5sum -c path/to/file.md5
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | md5sum: replace filename by path/to/file (#6465) | 2021-09-03T21:36:19 | [4887b989c62a](https://github.com/tldr-pages/tldr/commit/4887b989c62afb82c203695729f98f0c70af132a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | md5sum: add more information link (#5585) | 2021-03-30T15:30:51 | [3ba11ea0ed76](https://github.com/tldr-pages/tldr/commit/3ba11ea0ed76f2e0d416539366f9ea71822604d4)
[Flex Zhong](mailto:chungzh07@gmail.com) | hexo, heroku, md5sum: add Chinese translation (#4470) | 2020-10-05T16:28:31 | [edb523ee0bf5](https://github.com/tldr-pages/tldr/commit/edb523ee0bf5631becbc53f51d4c482af8cd7373)

