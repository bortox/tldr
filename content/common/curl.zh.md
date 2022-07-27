---
author: ['Andy Chen', 'KsRyY', 'Ein Verne', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1630394029
title: "curl, TLDR Pages"
description: "curl, 向 / 从一个服务器传输数据。"
categories: "common"
---
> 支持大多数协议，包括 HTTP, FTP, 和 POP3.

> 更多信息：<https://curl.se>.

- 将指定 URL 的内容下载到文件：

```bash
curl http://example.com --output 文件名
```

- 将文件从 URL 保存到由 URL 指示的文件名中：

```bash
curl --remote-name http://example.com/filename
```

- 下载文件，跟随 重定向，并且自动 续传（恢复）前序文件传输：

```bash
curl --remote-name --location --continue-at - http://example.com/filename
```

- 发送表单编码数据（`application/x-www-form-urlencoded` 的 POST 请求）：

```bash
curl --data 'name=bob' http://example.com/form
```

- 发送带有额外请求头，使用自定义请求方法的请求：

```bash
curl --header 'X-My-Header: 123' --request PUT http://example.com
```

- 发送 JSON 格式的数据，并附加正确的 `Content-Type` 请求头：

```bash
curl --data '{"name":"bob"}' --header 'Content-Type: application/json' http://example.com/users/1234
```

- 使用用户名和密码，授权访问服务器：

```bash
curl --user myusername:mypassword http://example.com
```

- 为指定资源使用客户端证书和密钥，并且跳过证书验证：

```bash
curl --cert client.pem --key key.pem --insecure https://example.com
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Andy Chen](mailto:andy200511@126.com) | curl: finish remaining Chinese translation | 2019-08-26T02:09:41 | [d00343a5adae](https://github.com/tldr-pages/tldr/commit/d00343a5adae280375864cabd6a89d12275ed095)
[Andy Chen](mailto:andy200511@126.com) | curl: revise translation | 2019-08-26T02:09:41 | [afccf5332152](https://github.com/tldr-pages/tldr/commit/afccf5332152fdc5189906fb98bc08bcbea77a69)
[KsRyY](mailto:andy200511@126.com) | curl: do more translation | 2019-08-26T02:09:41 | [a45aa7d112f3](https://github.com/tldr-pages/tldr/commit/a45aa7d112f3ac7752e8d2d156e656ed8c186b77)
[KsRyY](mailto:andy200511@126.com) | curl: add Chinese translaion (partial) | 2019-08-26T02:09:41 | [45d086c4599f](https://github.com/tldr-pages/tldr/commit/45d086c4599ff012a8d87626ae5c92ce990f926c)

