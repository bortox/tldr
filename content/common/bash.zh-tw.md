---
author: ['lincc', 'marchersimon']
date: 1630394029
title: "bash"
description: "bash, Bourne-Again SHell. 一個與 `sh` 兼容的命令列。"
categories: "common"
---
> 參照 `histexpand` 以使用 history expansion 特性。

> 更多資訊：<https://gnu.org/software/bash/>.

- 開啟互動式 shell：

```bash
bash
```

- 執行指令然後退出：

```bash
bash -c "指令"
```

- 執行腳本：

```bash
bash sh檔
```

- 執行腳本，每個指令執行之前先在命令列印出該指令：

```bash
bash -x sh檔
```

- 執行腳本，執行錯誤時，終止執行該腳本：

```bash
bash -e sh檔
```

- 從標準輸入 (stdin) 讀取並執行指令：

```bash
bash -s
```

- 在終端機印出 bash 的版本資訊 （`$BASH_VERSION` 只包含版本號)：

```bash
bash --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | bash: add traditional Chinese translation (#6191) | 2021-07-06T12:35:31 | [46676178ea8d](https://github.com/tldr-pages/tldr/commit/46676178ea8d507709e4776f21b4e1316ea9e90c)

