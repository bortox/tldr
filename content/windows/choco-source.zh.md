---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "choco source"
description: "choco source, 使用 Chocolatey 管理包的源。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-source>.

- 列出当前可用的源：

```bash
choco source list
```

- 添加一个新的包源：

```bash
choco source add --name 名称 --source url
```

- 添加包含凭据的新包源：

```bash
choco source add --name 名称 --source url --user 用户名 --password 密码
```

- 使用客户端证书添加新的包源：

```bash
choco source add --name 名称 --source url --cert 证书的路径
```

- 启用一个包源：

```bash
choco source enable --name 名称
```

- 禁用一个包源：

```bash
choco source disable --name 名称
```

- 移除一个包源：

```bash
choco source remove --name 名称
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-source: add Chinese translation | 2019-03-12T12:56:23 | [e87c68b9079d](https://github.com/tldr-pages/tldr/commit/e87c68b9079d2ec551fd6c686cb2f499f7a51ae4)

