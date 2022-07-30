---
author: ['Minghao Liu']
date: 1658675487
title: "chmod"
description: "chmod, 修改文件或目录的访问权限。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/chmod>.

- 授予所有者［u］执行［x］文件的权限：

```bash
chmod u+x 文件
```

- 授予所有者［u］读［r］和写［w］文件或目录的权限：

```bash
chmod u+rw 文件或目录
```

- 移除用户组［g］的文件执行［x］权限：

```bash
chmod g-x 文件
```

- 授予所有用户［a］读［r］以及执行［x］文件的权限：

```bash
chmod a+rx 文件
```

- 授予其他用户［o］（不在所有者用户组）和用户组［g］同样的权限：

```bash
chmod o=g 文件
```

- 移除其他用户［o］的所有权限：

```bash
chmod o= 文件
```

- 递归授予用户组［g］和其他用户［o］目录下所有文件和子目录的写［w］权限：

```bash
chmod -R g+w,o+w 目录
```

- 递归授予所有用户［a］目录下文件的读［r］权限和子目录的执行［X］权限：

```bash
chmod -R a+rX 目录
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | awk, chmod, chown: add Chinese translation (#8243) | 2022-07-24T17:11:27 | [d4edd1c122ee](https://github.com/tldr-pages/tldr/commit/d4edd1c122ee5843037ccb1cb50205bcd4ca7711)

