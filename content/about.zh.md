---
date: 2021-11-17
title: "关于TLDR Pages"
description: "什么是 TLDR Pages? 如何贡献？这个网站是什么？"
---

> 警告：这个页面是自动翻译的 - 不像本网站的TLDR Pages - 所以可能有翻译错误

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

## 什么是tldr-pages？

**tldr-pages**项目是一个合作维护的帮助页面的集合。
的命令行工具，为传统的 "大数据 "提供了更简单、更方便的补充。
到传统的[man pages](https://en.wikipedia.org/wiki/Man_page)。

也许你是第一次接触命令行的世界？也许你有点生疏，或者不能总是记住`lsof`或`tar`等命令的参数？

在 "man tar "中解释的第一个选项是："这当然没有帮助。

```
-B块
   指定磁带机I/O的块大小，以512字节记录为单位。
   通常情况下，只有在向磁带机读写时才需要这个参数。
   而且通常甚至没有，因为默认的块大小为20条记录（10240字节）是非常普遍的。
```

似乎有空间让更简单的帮助页面专注于实际例子。
怎么样。

![显示tar命令的tldr客户端的SVG动画](/tldr-tar.svg)

> tar命令的TLDR页面也可以在这个网站上找到 [此链接](https://tldr.bortox.it/common/tar)

这个资源库就是这样：一个不断增长的例子集合。
用于最常见的UNIX、Linux、macOS、SunOS、Android和Windows命令行工具。

## 这个网站是什么？

本网站的目的是使TLDR页面，一个由社区管理的帮助页面的集合
对于网络用户来说，只需在他们最喜欢的搜索引擎中输入 "TLDR页面+命令名称"，就可以获得命令行工具_。

目前，通过简单的谷歌搜索，不可能找到一个命令的TLDR页面。在用英语以外的特定语言搜索命令时，情况甚至更糟，因为经常有缓慢和点击率高的网站。

事实上，这个网站还支持评论和分享，使TLDR页面变得 "网络友好"。

###分析、监测和公告

当然没有**的广告。

追踪是通过Matomo完成的。Matomo被设置为不收集**个人数据**[^1]，因此它符合GDPR，不需要横幅cookie。如果你想选择退出，[你可以在这里进行](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it)。

该网站在欧洲**托管，由PHP-Friends负责。根据web-carbon.com，数据中心使用的是**可持续的能源!

如果你想**支持**网站（我支付服务器的费用），你可以[**在这里捐献一些东西**]（https://bortox.it/contribuisci-cs-en）。

###为什么是这个网站？

1.为TLDR页面编制索引，并使其易于在网上以多种语言进行搜索
2.只是为了写东西

### 本网站是如何运作的？

* 从一个脚本中读取Markdown的TLDR源文件和相关的Git数据（30米）。
* Hugo兼容的页面是由脚本创建的
* 雨果在短短10秒内就创建了这个网站（~6500页）！***。

###可能的新功能

- [] 参与特定的页面
- 自动翻译，DeepL（免费版最高50万字/月）。


##如何使用

在你自己的电脑上访问这些网页的一种流行和方便的方式
是安装【Node.js客户端】（https://github.com/tldr-pages/tldr-node-client）。
这是由tldr-pages项目的维护者支持的。

``sh
npm install -g tldr
```

另外，你可以使用[Python客户端](https://github.com/tldr-pages/tldr-python-client)，它可以通过`pip3`安装。

``sh
pip3 安装 tldr
```

这使你可以直接访问一个简化的、易于阅读的命令指南，如`tar`。
通过输入`tldr tar`而不是正常的`man tar`来访问。

如果你想要一个不需要安装任何软件的离线版本。
见[PDF版本]（https://tldr.sh/assets/tldr-book.pdf）。

要浏览而不在你的电脑上安装客户端
见<https://tldr.ostera.io>上的网络客户端。

还有**社区提供的各种其他客户**。
无论是在命令行还是在其他平台上。
完整的客户名单，见我们的[wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients)。


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

私たちは、[歓迎と協力](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md)のコミュニティを維持することに努めます。
初めて投稿される方は、[投稿ガイドライン](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md)をご覧になり、ぜひ始めてみてください。

翻訳にご協力いただける方は、<https://lukwebsforge.github.io/tldri18n/>までご連絡ください。
をクリックすると、すべての翻訳の全体的な進捗状況を確認でき、どの翻訳が不足しているか、または古くなっているかを知ることができます。

## 'tldr'の意味は？

TL;DRとは、「Too long; I have not read」の略です。
インターネットの専門用語に由来し、長いテキスト（またはその一部）が
(またはその一部)は、長すぎるためスキップされています。
詳細はHow-To Geekの[記事]（https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/）でご確認ください。

[^1]: 訪問者ログなし、クッキーなしのトラッキング、[matomo公式ガイド](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/)に従って匿名化されたIPアドレス（192.168.xxx.xxxのように2バイト） ... 