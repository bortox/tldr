---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'Starccy', 'marchersimon']
date: 1648358715
title: "asciinema, TLDR Pages"
description: "asciinema, 录制和播放终端会话，也可以把他们分享到 asciinema.org."
categories: "common"
---
> 更多信息：<https://asciinema.org/>.

- 将本地安装的`asciinema`与 asciinema.org 账号关联：

```bash
asciinema auth
```

- 进行新的录制（完成后，将提示用户上传或在本地保存）：

```bash
asciinema rec
```

- 进行新的录制，保存到本地的文件中：

```bash
asciinema rec 文件路径.cast
```

- 从本地文件中播放终端录屏：

```bash
asciinema play 文件路径.cast
```

- 在 asciinema.org 中播放终端录屏：

```bash
asciinema play https://asciinema.org/a/文件 ID
```

- 进行新的录制，将闲置时间设置为最多 2.5 秒：

```bash
asciinema rec -i 2.5
```

- 打印本地保存的录像的完整输出：

```bash
asciinema cat 文件路径.cast
```

- 从本地上传一个录屏到 asciinema.org：

```bash
asciinema upload 文件路径.cast
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | asciinema: add Chinese translation | 2019-04-17T21:44:55 | [75426d21f3eb](https://github.com/tldr-pages/tldr/commit/75426d21f3eb79e1d1615b117f6d51bc6835bc32)
[Starccy](mailto:452276725@qq.com) | asciinema: add Chinese translation | 2019-04-17T21:44:55 | [7493c1db827b](https://github.com/tldr-pages/tldr/commit/7493c1db827b5821e3f761f03ada29988d7dbe7e)

