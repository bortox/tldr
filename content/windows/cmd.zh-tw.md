---
author: ['Poy Chang', 'Seth Falco']
date: 1648358715
title: "cmd"
description: "cmd, Windows 命令解釋器。"
categories: "windows"
---
> 更多資訊：<https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- 開啟一個新的命令列執行個體：

```bash
cmd
```

- 執行指定的命令然後退出：

```bash
cmd /c "命令"
```

- 執行一個指定的命令，之後進入一個互動式 shell：

```bash
cmd /k "命令"
```

- 不顯示命令的輸出結果：

```bash
cmd /q
```

- 啟用或禁用命令擴展：

```bash
cmd /e:on|off
```

- 啟用或禁用文件和目錄名的自動補全：

```bash
cmd /f:on|off
```

- 啟用或禁用環境變數擴展：

```bash
cmd /v:on|off
```

- 使用 Unicode 編碼強制輸出內容：

```bash
cmd /u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Poy Chang](mailto:poypost@gmail.com) | cmd: add traditional Chinese translation (#7081) | 2021-10-26T09:42:13 | [1c2dc4bbc855](https://github.com/tldr-pages/tldr/commit/1c2dc4bbc8559b3b27a5c7a01b83c80ed1c90e0b)

