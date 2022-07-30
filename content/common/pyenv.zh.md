---
author: ['meowmeowcat']
date: 1636827201
title: "pyenv"
description: "pyenv, 在多个 Python 版本之间轻松切换。"
categories: "common"
---
> 更多信息：<https://github.com/pyenv/pyenv>.

- 列出所有可用的命令：

```bash
pyenv commands
```

- 列出 `${PYENV_ROOT}/versions` 目录下的所有 Python 版本：

```bash
pyenv versions
```

- 在 `${PYENV_ROOT}/versions` 目录下安装一个 Python 版本：

```bash
pyenv install 2.7.10
```

- 在 `${PYENV_ROOT}/versions` 目录下卸载一个 Python 版本：

```bash
pyenv uninstall 2.7.10
```

- 设置在当前机器中全局使用的 Python 版本：

```bash
pyenv global 2.7.10
```

- 设置在当前目录及其下所有目录中使用的 Python 版本：

```bash
pyenv local 2.7.10
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | pyenv: add Chinese translation (#7427) | 2021-11-13T19:13:21 | [b8877dbc816e](https://github.com/tldr-pages/tldr/commit/b8877dbc816eed245cc1bd660ed7fe5a617c03b5)

