---
author: ['Jonathan Reyes', 'あでり', 'marchersimon']
date: 1643311827
title: "dig"
description: "dig, DNS 情報を調べるユーティリティーです。"
categories: "common"
---
> 詳しくはこちら: <https://manned.org/dig>

- ホスト名に関連する IP を検索（A レコード）:

```bash
dig +short example.com
```

- 指定したドメインの詳細な回答を得る（A レコード）:

```bash
dig +noall +answer example.com
```

- 指定されたドメイン名に関連する特定の DNS レコードタイプを取得する:

```bash
dig +short example.com A|MX|TXT|CNAME|NS
```

- 指定したドメイン名のすべてのタイプのレコードを取得する:

```bash
dig example.com ANY
```

- 問い合わせる別の DNS サーバーを指定する:

```bash
dig @8.8.8.8 example.com
```

- IP アドレスの DNS 逆引きの実行（PTR レコード）:

```bash
dig -x 8.8.8.8
```

- ゾーンの権威ネームサーバーの検索と SOA レコードの表示:

```bash
dig +nssearch example.com
```

- ドメイン名を解決するための反復的なクエリの実行と、そのトレースパス全体を表示する:

```bash
dig +trace example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | dig: fix more information link (#7724) | 2022-01-27T20:30:27 | [cbd3214b25ef](https://github.com/tldr-pages/tldr/commit/cbd3214b25ef91e2590438cc9669c02f28720ce8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

