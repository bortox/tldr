---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "mysql"
description: "mysql, MySQL のコマンドラインツールです。"
categories: "common"
---
> 詳しくはこちら: <https://www.mysql.com/>

- データベースへの接続:

```bash
mysql データベース名
```

- データベースへの接続、ユーザーにはパスワードの入力が求められる:

```bash
mysql -u ユーザー --password データベース名
```

- 別のホスト上のデータベースに接続する:

```bash
mysql -h データベースホスト データベース名
```

- Unix ソケット経由でのデータベースへの接続:

```bash
mysql --socket ソケットファイルへのパス
```

- スクリプトファイル（バッチファイル）での SQL 文の実行:

```bash
mysql -e "source sqlファイル" データベース名
```

- `mysqldump` で作成したバックアップからデータベースをリストアする（ユーザーはパスワードの入力を求められます）:

```bash
mysql --user ユーザー --password データベース名 < バックアップsqlファイルへのパス
```

- バックアップからすべてのデータベースを復元する（ユーザーはパスワードの入力を求められます）:

```bash
mysql --user ユーザー --password < バックアップsqlファイルへのパス
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

