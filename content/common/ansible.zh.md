---
author: ['bl-ue', 'Ein Verne', 'Lucas Gabriel Schneider', 'Starccy', 'marchersimon']
date: 1633112881
title: "ansible, TLDR Pages"
description: "ansible, 通过 SSH 协议远程管理计算机组。使用 `/etc/ansible/hosts` 文件来添加组 / 主机。"
categories: "common"
---
> 此命令也有关于其子命令的文件，例如：`ansible galaxy`.

> 更多信息：<https://www.ansible.com/>.

- 列出给定组下的所有主机：

```bash
ansible 组 --list-hosts
```

- 调用 ping 模块来 ping 一组主机：

```bash
ansible 组 -m ping
```

- 通过调用安装模块来显示关于一组主机的信息：

```bash
ansible 组 -m setup
```

- 调用命令模块并使用给定的参数来对一组主机执行命令：

```bash
ansible 组 -m command -a '命令'
```

- 以管理员权限执行一个命令：

```bash
ansible 组 --become --ask-become-pass -m command -a '命令'
```

- 使用自定义的清单文件执行一个命令：

```bash
ansible 组 -i 清单文件 -m command -a '命令'
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ansible: add Chinese translation | 2019-04-17T21:44:55 | [f8279f3d5c15](https://github.com/tldr-pages/tldr/commit/f8279f3d5c156fbcb5ecf5555949148328eeb77a)
[Starccy](mailto:452276725@qq.com) | ansible: add Chinese translation | 2019-04-17T21:44:55 | [435e0d89eeeb](https://github.com/tldr-pages/tldr/commit/435e0d89eeeb71ee5df0e22e03e233c0164b7e4c)

