---
author: ['Minghao Liu']
date: 1658675487
title: "awk"
description: "awk, 一种用于文件处理的通用编程语言。"
categories: "common"
---
> 更多信息：<https://github.com/onetrueawk/awk>.

- 以空格为分隔符，打印文件每行第五列（也称作字段）：

```bash
awk '{print $5}' 文件名
```

- 以空格为分隔符，打印文件包含“foo” 的所有行的第二列：

```bash
awk '/foo/ {print $2}' 文件名
```

- 以逗号而不是空格作为分隔符，打印文件每行的最后一列：

```bash
awk -F ',' '{print $NF}' 文件名
```

- 计算文件的第一列数值之和并打印：

```bash
awk '{s+=$1} END {print s}' 文件名
```

- 从第一行开始，每三行打印一行：

```bash
awk 'NR%3==1' 文件名
```

- 根据条件不同，打印不同内容：

```bash
awk '{if ($1 == "foo") print "Exact match foo"; else if ($1 ~ "bar") print "Partial match bar"; else print "Baz"}' 文件名
```

- 打印第 10 列等于指定值的所有行：

```bash
awk '($10 == 指定值)'
```

- 打印第 10 列介于最小值和最大值之间的所有行：

```bash
awk '($10 >= 最小值 && $10 <= 最大值)'
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | awk, chmod, chown: add Chinese translation (#8243) | 2022-07-24T17:11:27 | [d4edd1c122ee](https://github.com/tldr-pages/tldr/commit/d4edd1c122ee5843037ccb1cb50205bcd4ca7711)

