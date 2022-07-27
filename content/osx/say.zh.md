---
author: ['wizarot', 'meowmeowcat', 'Ein Verne', 'Guido Lena Cota', 'bl-ue']
date: 1635858124
title: "say, TLDR Pages"
description: "say, 将文本转换为语音。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/say.html>.

- 大声说出一个句子：

```bash
say "你好，世界！"
```

- 播放文本文件内容音频：

```bash
say -f 文件名.txt
```

- 用自定义的语音和语音速率说出一个句子：

```bash
say -v 语音库名 -r 每分钟多少词 "你好，我可以说中文."
```

- 列出可用的语音库：

```bash
say --voice="?"
```

- 创建文本的音频文件：

```bash
say -o 文件名.aiff "你好，请将录音内容输出到文件."
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | say: add Chinese translation | 2019-03-15T12:47:29 | [dbe04b2f08e4](https://github.com/tldr-pages/tldr/commit/dbe04b2f08e4838b1dc542e67a2d2620686a9d3e)

