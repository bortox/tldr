---
date: 2021-11-17
title: "TLDR Pagesについて"
description: "TLDR Pagesとは何ですか？投稿するには？このウェブサイトは何ですか？"
---

> 警告: このページは自動翻訳されています - このウェブサイトのTLDR Pagesとは異なります - そのため、翻訳エラーが発生する可能性があります。

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

## tldr-pagesとは？

tldr-pages**プロジェクトは、共同で管理されているヘルプページのコレクションです。
を補完する、よりシンプルでアクセスしやすいコマンドラインツールです。
を従来の[man pages](https://en.wikipedia.org/wiki/Man_page)に変更しました。

もしかしたら、あなたはコマンドラインの世界に初めて触れるかもしれませんね。もしかしたら、少し錆びついていたり、 `lsof` や `tar` のようなコマンドの引数をいつも覚えていないかもしれませんね？

確かに`man tar`で説明されている最初のオプションは救いようがないですね。

```
-bブロック
   テープドライブI/Oのブロックサイズを512バイトのレコードで指定します。
   通常、この引数はテープドライブに読み書きするときのみ必要です。
   というのも、デフォルトのブロックサイズは20レコード（10240バイト）であることが非常に多いからです。
```

実用例に重点を置いた、よりシンプルなヘルプページを作成する余地がありそうです。
どうでしょう。

![tarコマンドを表示するtldrクライアントのアニメーションSVG](/tldr-tar.svg)

> tarコマンドのTLDRページは、こちらのサイトでもご覧いただけます。[このリンク]("https://tldr.bortox.it/content/common/tar")

このリポジトリは、まさに「常に増え続けるサンプルのコレクション」です。
UNIX、Linux、macOS、SunOS、Android、Windowsのコマンドラインツールのうち、最も一般的なものを対象としています。

## このサイトは何ですか？

このサイトの目的は、コミュニティが管理するヘルプページの集合体であるTLDR Pagesを
TLDR pages + command_name' と検索エンジンに入力するだけで、コマンドラインツール_をウェブユーザーに提供することができます。

現在、Googleで検索するだけでは、コマンドのTLDRページを見つけることはできません。英語以外の特定の言語でコマンドを検索する場合は、遅いサイトやクリックベイトのサイトが多いため、状況はさらに悪化します。

実際、このサイトはコメントや共有もサポートしており、TLDRのページを「ウェブフレンドリー」なものにしています。

### 分析・監視・発表

明らかに**広告がない**。

トラッキングはMatomoで行っています。Matomoは**個人情報**[^1]を収集しない設定になっているため、GDPRに準拠し、バナークッキーも必要ありません。オプトアウトを希望される場合は、[こちらで受け付けています](](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it)。

このサイトは、PHP-Friendsによってヨーロッパでホストされています。web-carbon.comによると、このデータセンターは**持続可能なエネルギー**を使用しているとのことです。

もしあなたがこのサイトを**サポート**したいのであれば（私はサーバー代を支払っています）、[**donate something here**](https://bortox.it/contribuisci-cs-en)を使ってください。

### なぜこのサイトなのか？

1. TLDRのページをインデックス化し、多言語で簡単にオンライン検索ができるようにする。
2.ただ何かを書くこと

### このサイトはどのように機能するのですか？

* Markdownで書かれたTLDRソースファイルと関連するGitデータをスクリプトから読み込みます（30m）。
* Hugo互換のページはスクリプトで作成されます。
Hugoは、このウェブサイト（〜6500ページ）をわずか10秒で作成しました！ * Hugoは、このウェブサイト（〜6500ページ）をわずか10秒で作成しました。

### 新機能の可能性

- [ ] エンゲージメント専用ページ
- DeepLによる自動翻訳（無料版では最大50万文字/月）


## How to use

自分のパソコンでこれらのページにアクセスできる、人気のある便利な方法です。
は、[Node.jsクライアント](https://github.com/tldr-pages/tldr-node-client)をインストールすることです。
は、tldr-pages プロジェクトのメンテナによってサポートされています。

``sh
npm install -g tldr
```

また、[Pythonクライアント](https://github.com/tldr-pages/tldr-python-client)を利用することもできます。これは `pip3` 経由でインストールすることができます。

``sh
pip3 install tldr
```

これは `tar` のようなコマンドの簡略化された読みやすいガイドに直接アクセスできるようにするものです。
は、通常の `man tar` の代わりに `tldr tar` とタイプすることでアクセスできます。

ソフトウェアをインストールしないオフライン版をご希望の場合。
PDF版](https://tldr.sh/assets/tldr-book.pdf)をご覧ください。

コンピュータにクライアントをインストールせずにブラウズするには
は、ウェブクライアント（<https://tldr.ostera.io>）を参照してください。

また、コミュニティが提供する**様々なクライアント**があります。
コマンドライン用と他のプラットフォーム用の両方があります。
クライアントの全リストは、弊社の[wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients)をご覧ください。


## How can I contribute to tldr-pages?

すべての投稿を歓迎します。

貢献の方法には、以下のようなものがあります。

- カバーされていないお気に入りのコマンドを追加する。
- 既存ページの事例追加や内容の改善。
- ヘルプウォンテッド](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)ラベルを持つ我々の問題から要求されたページを追加することです。
- ページの各国語への翻訳。

すべての `tldr` ページは Markdown で書かれているので、非常に簡単に編集することができ、変更内容は
を使用して、コマンドラインから、あるいは
をGitHubのウェブインタフェースで表示します。

私たちは、[歓迎と協力](GOVERNANCE.md)のコミュニティを維持することに努めます。
初めて投稿される方は、[投稿ガイドライン](CONTRIBUTING.md)をご覧になり、ぜひ始めてみてください。

翻訳にご協力いただける方は、<https://lukwebsforge.github.io/tldri18n/>までご連絡ください。
をクリックすると、すべての翻訳の全体的な進捗状況を確認でき、どの翻訳が不足しているか、または古くなっているかを知ることができます。

## 'tldr'の意味は？

TL;DRとは、「Too long; I have not read」の略です。
インターネットの専門用語に由来し、長いテキスト（またはその一部）が
(またはその一部)は、長すぎるためスキップされています。
詳細はHow-To Geekの[記事]（https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/）でご確認ください。

[^1]: 訪問者ログなし、クッキーなしのトラッキング、[matomo公式ガイド](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/)に従って匿名化されたIPアドレス（192.168.xxx.xxxのように2バイト） ... 