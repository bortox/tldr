---
author: ['bl-ue', 'Flex Zhong', 'marchersimon']
date: 1630394029
title: "takeown"
description: "takeown, 取得文件或目录的所有权。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/takeown>.

- 取得指定文件的所有权：

```bash
takeown /f 路径/文件
```

- 取得指定目录的所有权：

```bash
takeown /d 路径/目录
```

- 取得指定目录和所有子目录的所有权：

```bash
takeown /r /d 路径/目录
```

- 将所有权更改为管理员组，而不是当前用户：

```bash
takeown /a /f 路径/文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | scoop-bucket, wsl, takeown: add Chinese translation (#4604) * scoop-bucket: add Chinese translation * wsl: add Chinese translation * [...] | 2020-10-12T23:06:25 | [dd2fee0c190e](https://github.com/tldr-pages/tldr/commit/dd2fee0c190e950d33a12941482637e2387216bc)

