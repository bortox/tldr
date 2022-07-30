---
author: ['千玄子', 'lmh', 'Ein Verne', 'Marco Bonelli', 'bl-ue', 'marchersimon']
date: 1630394029
title: "at"
description: "at, 在指定时间执行命令。"
categories: "linux"
---
> 更多信息：<https://man.archlinux.org/man/at.1>.

- 打开 `at` 提示符创建一组新的定时命令，按 `Ctrl + D` 保存并退出：

```bash
at hh:mm
```

- 运行命令并通过本地电子邮件程序（例如 sendmail）发送运行结果：

```bash
at hh:mm -m
```

- 在指定时间执行一个脚本：

```bash
at hh:mm -f 文件路径
```

- 在二月十八号下午十一点发送系统通知：

```bash
echo "notify-send 'Wake up!'" | at 11pm Feb 18
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser, apt-*, apt, aptitude, at: update Chinese translation (#6400) | 2021-08-23T21:25:59 | [ff74227350e9](https://github.com/tldr-pages/tldr/commit/ff74227350e9b89a9501ddbf39089ed60876201c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | archey, arp-scan, as, aspell, at: remove execute permission (#5243) | 2021-02-11T14:08:59 | [de72bdb4f8da](https://github.com/tldr-pages/tldr/commit/de72bdb4f8dab69bee04f4cd80bdab935c90f654)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | refactor: fix newlines removing carriage returns (#2880) | 2019-04-10T11:49:16 | [51e3430a3883](https://github.com/tldr-pages/tldr/commit/51e3430a3883b604de4f986f80368e9252c65b94)
[lmh](mailto:hugue_liu@yahoo.com) | at: add Chinese translation. | 2019-02-13T16:10:51 | [5669a98d5238](https://github.com/tldr-pages/tldr/commit/5669a98d523847177f8918e90eb3aa80cc583347)

