---
author: ['Andy Li']
date: 1636318777
title: "curl"
description: "curl, 向 / 從一個伺服器傳輸數據。"
categories: "common"
---
> 支持大多數協議，包括 HTTP、FTP 和 POP3.

> 更多資訊：<https://curl.se>.

- 將指定 URL 的內容下載到檔案：

```bash
curl http://example.com --output 檔案/完整/路徑
```

- 將檔案從 URL 保存到由 URL 指示的檔名：

```bash
curl --remote-name http://example.com/filename
```

- 下載檔案，跟隨重新導向，並且自動續傳（恢復）前序檔案傳輸：

```bash
curl --remote-name --location --continue-at - http://example.com/filename
```

- 發送表單編碼數據（`application/x-www-form-urlencoded` 的 POST 請求）：

```bash
curl --data 'name=bob' http://example.com/form
```

- 發送帶有額外請求頭，使用自定義請求方法：

```bash
curl --header 'X-My-Header: 123' --request PUT http://example.com
```

- 發送 JSON 格式的數據，並附加正確的 `Content-Type` 請求頭：

```bash
curl --data '{"name":"bob"}' --header 'Content-Type: application/json' http://example.com/users/1234
```

- 透過使用者名稱和密碼訪問伺服器：

```bash
curl --user myusername:mypassword http://example.com
```

- 爲指定資源使用客戶端憑證和密鑰，並且跳過憑證驗證：

```bash
curl --cert client.pem --key key.pem --insecure https://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andy Li](mailto:andy@onthewings.net) | curl: add traditional Chinese translation (#7289) | 2021-11-07T21:59:37 | [c308f2bca2c4](https://github.com/tldr-pages/tldr/commit/c308f2bca2c40044a9a7741e70f412bc9a72835b)

