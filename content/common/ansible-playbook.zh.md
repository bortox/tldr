---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "ansible-playbook, TLDR Pages"
description: "ansible-playbook, 通过 SSH 协议在远程计算机上执行 playbook 中定义的任务。"
categories: "common"
---
> 更多信息：<https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- 执行 playbook 中的任务：

```bash
ansible-playbook playbook
```

- 在给定的主机清单文件中执行 playbook 中的命令：

```bash
ansible-playbook playbook -i 清单文件
```

- 通过定义在命令行中额外的变量执行 playbook 中的任务：

```bash
ansible-playbook playbook -e "变量 1=值 1 变量 2=值 2"
```

- 通过定义在一个 json 格式的文件中额外的变量执行 playbook 中的任务：

```bash
ansible-playbook playbook -e "@variables.json"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ansible-playbook: add Chinese translation | 2019-04-17T21:44:55 | [46151609cb4f](https://github.com/tldr-pages/tldr/commit/46151609cb4f2d4c13c95c427f8a8d0cb0c2ef5f)
[Starccy](mailto:452276725@qq.com) | ansible-playbook: add Chinese translation | 2019-04-17T21:44:55 | [78dd8048c0ec](https://github.com/tldr-pages/tldr/commit/78dd8048c0ec6e21aaab25fe854db686176be1e0)

