---
author: ['Flex Zhong', 'bl-ue', 'marchersimon']
date: 1630394029
title: "heroku, TLDR Pages"
description: "heroku, 从命令行创建和管理 Heroku 应用。"
categories: "common"
---
> 更多信息：<https://www.heroku.com/>.

- 登录到你的 heroku 帐户：

```bash
heroku login
```

- 创建一个 heroku 应用：

```bash
heroku create
```

- 显示应用的日志：

```bash
heroku logs --app app_name
```

- 在 dyno（Heroku 虚拟机）中运行一次性进程：

```bash
heroku run process_name --app app_name
```

- 列出应用的 dyno（Heroku 虚拟机）：

```bash
heroku ps --app app_name
```

- 永久销毁应用：

```bash
heroku destroy --app app_name
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | hexo, heroku, md5sum: add Chinese translation (#4470) | 2020-10-05T16:28:31 | [edb523ee0bf5](https://github.com/tldr-pages/tldr/commit/edb523ee0bf5631becbc53f51d4c482af8cd7373)

