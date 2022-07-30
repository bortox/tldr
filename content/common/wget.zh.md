---
author: ['Ein Verne', 'Nicolas Kosinski', 'KsRyY', 'Andy Chen', 'bl-ue', 'marchersimon']
date: 1630394029
title: "wget"
description: "wget, 从网络上下载文件。"
categories: "common"
---
> 支持 HTTP, HTTPS, 和 FTP.

> 更多信息：<https://www.gnu.org/software/wget>.

- 将该 URL 的内容下载到文件中（在这个例子中文件名为 "foo"）：

```bash
wget https://example.com/foo
```

- 将该 URL 的内容下载到文件中（在这个例子中文件名为 "bar"）：

```bash
wget --output-document bar https://example.com/foo
```

- 以每三秒一个请求的速度下载一个网页和其所有资源（脚本，样式表，图片等等）：

```bash
wget --page-requisites --convert-links --wait=3 https://example.com/somepage.html
```

- 从一个目录中下载所有列出的文件和其所有子文件夹（不下载内嵌网页）：

```bash
wget --mirror --no-parent https://example.com/somepath/
```

- 限制下载速度和重试次数：

```bash
wget --limit-rate=300k --tries=100 https://example.com/somepath/
```

- 使用基本授权来从 HTTP/FTP 服务器中下载文件：

```bash
wget --user=username --password=password https://example.com
```

- 继续一个未完成的下载任务：

```bash
wget --continue https://example.com
```

- 将指定文件中所有列出的 URL 下载到一个目录中：

```bash
wget --directory-prefix path/to/directory --input-file URLs.txt
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | wget: use long arguments (#5879) | 2021-05-04T09:25:49 | [5d01dae43fae](https://github.com/tldr-pages/tldr/commit/5d01dae43fae9f8dcf5d5f1d7df2d7104ece7907)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Andy Chen](mailto:andy200511@126.com) | wget: finish remaining Chinese translation | 2019-08-26T02:09:41 | [50257b3c955f](https://github.com/tldr-pages/tldr/commit/50257b3c955fc7ffcee89b9f08bd5ba648af84c8)
[Andy Chen](mailto:andy200511@126.com) | wget: revise translation | 2019-08-26T02:09:41 | [c20b2b3d2495](https://github.com/tldr-pages/tldr/commit/c20b2b3d2495bb1af3fca111f3663d8d7291b380)
[KsRyY](mailto:andy200511@126.com) | wget: add Chinese translation | 2019-08-26T02:09:41 | [0ceaa59cf2f3](https://github.com/tldr-pages/tldr/commit/0ceaa59cf2f328c39403f09664171964eb03d7ec)

