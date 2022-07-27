---
author: ['WhiredPlanck', 'marchersimon']
date: 1630394029
title: "iptables, TLDR Pages"
description: "iptables, 可用于配置 Linux 内核防火墙提供的过滤表、规则链和规则的程序。"
categories: "linux"
---
> 更多信息：<https://www.netfilter.org/projects/iptables/>.

- 查看过滤表的规则链、规则以及数据包/字节计数器：

```bash
sudo iptables -vnL
```

- 设定规则链策略规则：

```bash
sudo iptables -P 规则链 规则
```

- 追加规则到 IP 的规则链策略：

```bash
sudo iptables -A 规则链 -s ip -j 规则
```

- 追加规则到 IP 的规则链策略（考虑协议与端口）：

```bash
sudo iptables -A 规则链 -s ip -p 协议 --dport 端口 -j 规则
```

- 删除规则链中的规则：

```bash
sudo iptables -D 规则链 规则所在行号
```

- 将指定过滤表的 iptables 配置保存到文件中：

```bash
sudo iptables-save -t 过滤表名 > iptables_文件路径
```

- 从文件中还原 iptables 配置：

```bash
sudo iptables-restore < iptables_文件路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[WhiredPlanck](mailto:47623588+whriedplanck@users.noreply.github.com) | acpi, flatpak, i3, iptables: add Chinese translation (#5061) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-01T23:26:50 | [66da99825c17](https://github.com/tldr-pages/tldr/commit/66da99825c17d7f5c97e61f7eb01218e8edb5449)

