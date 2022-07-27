---
author: ['errorcode']
date: 1628875176
title: "grub-mkconfig, TLDR Pages"
description: "grub-mkconfig, 生成GRUB配置文件。"
categories: "linux"
---
> 更多信息：<https://www.gnu.org/software/grub/manual/grub/html_node/Invoking-grub_002dmkconfig.html>.

- 模拟运行并打印配置到标准输出：

```bash
sudo grub-mkconfig
```

- 生成配置文件：

```bash
sudo grub-mkconfig --output=/boot/grub/grub.cfg
```

- 打印帮助页面：

```bash
grub-mkconfig --help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[errorcode](mailto:errorcode7@qq.com) | cp, grub-install, grub-mkconfig, hexdump, readelf: add Chinese translation (#6278) | 2021-08-13T19:19:36 | [39b5be991a84](https://github.com/tldr-pages/tldr/commit/39b5be991a84323b8fa746ce688cf044240b9752)

