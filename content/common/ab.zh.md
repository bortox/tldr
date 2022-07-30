---
author: ['Ein Verne', 'jinsihou19', 'bl-ue', 'Starccy', 'marchersimon']
date: 1635234067
title: "ab"
description: "ab, Apache 基准测试工具。"
categories: "common"
---
> 更多信息：<https://httpd.apache.org/docs/current/programs/ab.html>.

- 向目标 URL 执行 100 次 HTTP GET 请求：

```bash
ab -n 100 url
```

- 使用 10 个并发请求，同时向目标 URL 执行 100 次 HTTP GET 请求：

```bash
ab -n 100 -c 10 url
```

- 使用来自文件的 JSON 负载对 URL 执行 100 个 HTTP POST 请求：

```bash
ab -n 100 -T application/json -p path/to/file.json url
```

- 使用 HTTP [K]eep Alive，即在一个 HTTP 会话中执行多个请求：

```bash
ab -k url
```

- 为基准测试设置最大的测试时间（单位：秒）：

```bash
ab -t 60 url
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[jinsihou19](mailto:540097546@qq.com) | ab: update Chinese translation (#7148) | 2021-10-26T09:41:07 | [807a6d07c585](https://github.com/tldr-pages/tldr/commit/807a6d07c585c39b64d4b62239a4186c98299fdc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ab: add Chinese translation | 2019-04-17T21:44:55 | [0b7dc8f822a3](https://github.com/tldr-pages/tldr/commit/0b7dc8f822a38ef864bd052fe684595b9f9fce52)

