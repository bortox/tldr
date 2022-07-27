---
author: ['wizarot', 'meowmeowcat', 'bl-ue']
date: 1636919159
title: "shutdown, TLDR Pages"
description: "shutdown, 关闭并重新启动系统。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/shutdown.html>.

- 立即关机：

```bash
shutdown -h now
```

- 立即休眠：

```bash
shutdown -s now
```

- 立即重启：

```bash
shutdown -r now
```

- 倒计时 5 分钟重启：

```bash
shutdown -r +5
```

- 在下午 1:00（使用 24 小时时钟）关机：

```bash
shutdown -h 1300
```

- 在 2042 年 5 月 10 日上午 11:30 重新启动（输入格式：年年月月日日时时分分）：

```bash
shutdown -r 4205101130
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | shutdown: update Chinese translation (#7430) | 2021-11-13T19:08:10 | [1f1071c77ce5](https://github.com/tldr-pages/tldr/commit/1f1071c77ce568868e95ea62eb6368ebf1aa5b76)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[wizarot](mailto:wizarot@qq.com) | shutdown: add Chinese translation | 2019-03-15T12:47:29 | [73490d15af64](https://github.com/tldr-pages/tldr/commit/73490d15af64f8c5ce84515455e556e259c610a4)

