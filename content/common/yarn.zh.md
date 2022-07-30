---
author: ['Ein Verne', 'bl-ue', 'KsRyY', 'marchersimon']
date: 1630394029
title: "yarn"
description: "yarn, JavaScript 和 Node.js package manager 的一个替代。"
categories: "common"
---
> 更多信息：<https://yarnpkg.com>.

- 全局安装一个模块：

```bash
yarn global add module_name
```

- 安装 `package.json` 中指定的依赖（`install` 命令是可选的 -- 你可以直接输入`yarn`）：

```bash
yarn install
```

- 安装一个模块并将其写入 `package.json` 中的依赖项（增加 `--dev` 来作为开发依赖写入）：

```bash
yarn add module_name@version
```

- 卸载一个模块并将其从 `package.json` 的依赖项中移除：

```bash
yarn remove module_name
```

- 交互式地创建一个 `package.json` 文件：

```bash
yarn init
```

- 确认一个模块是否是一个依赖项并且列出依赖其的模块：

```bash
yarn why module_name
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[KsRyY](mailto:andy200511@126.com) | yarn: add Chinese translation | 2019-08-26T02:09:41 | [0a1a6d12b3f2](https://github.com/tldr-pages/tldr/commit/0a1a6d12b3f22077d569827cb2d418c7eb61791e)

