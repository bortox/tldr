---
author: ['Flex Zhong', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "gh gist, TLDR Pages"
description: "gh gist, 在命令行上使用 GitHub Gists."
categories: "common"
---
> 更多信息：<https://cli.github.com/manual/gh_gist>.

- 从一个以空格分隔的文件列表中创建一个新的 Gist：

```bash
gh gist create 路径/文件
```

- 创建一个带有描述的新 Gist：

```bash
gh gist create 文件名 --desc "描述"
```

- 编辑一个 Gist：

```bash
gh gist edit id_或_url
```

- 列出当前登录用户所拥有的 Gist：

```bash
gh gist list --limit int
```

- 在默认浏览器中查看 Gist，且不渲染 Markdown：

```bash
gh gist view id_或_url --web --raw
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | gh-repo, gh-gist: add Chinese translation (#4950) | 2020-11-13T02:25:04 | [7cc95674bcd9](https://github.com/tldr-pages/tldr/commit/7cc95674bcd980ce26a9a1a28900e521b56e14ea)

